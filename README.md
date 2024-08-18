Автоматизация QA <sup>3.5 мес</sup>
================

Guidelines
==========

Формат обучения
---------------
- группа до 30 человек
- 1 вебинар в неделю по 2 часа (1.5 часа контент + 0.5 обсуждение вопросов)
- reference/выжимка по каждому вебинару
- задания для самостоятельной проработки ~2 часа трудоемкости в неделю
- разбор вопросов в slack-чате силами тренера и менторов
- два уровня самостоятельной практики: по целям и задачам
- отчуждаемые критерии выполнения практики

Что нужно для начала
--------------------
- [ ] Убедиться, что вы в slack-чате
- [ ] [Если нет] завести аккаунт на GitHub
- [x] Сделать форк данного репозитория с материалами
- [ ] Добавить в ваш новый репо своих менторов как коллабораторов
- [x] Установить jdk ≥11 и IntelliJ IDEA

Контакты
--------
- slack-чат 
- корпоративная почта: `a.roshchina`


Agenda <sup>14 недель</sup>
======
28 ак.ч.

Java Application Building <sup>1 вебинар, 1 неделя</sup>
-------------------------

### Local GIT versioning workflow <sup>15 мин</sup>
- [x] Why VCS? cool!!!!!
- [x] Local repo
- [x] Commit
- content: files A/M/D
- hash/id
- message
- [x] Branch
- `git log`

### Remote GIT versioning workflow <sup>15</sup>
- [x] Remote repo
- alias: `origin`
- [x] Clone
- mirror branches
- [x] Push
- [x] Pull

### Managing PRs with GitHub <sup>10</sup>
- [x] [PR workflow](https://www.earthdatascience.org/images/earth-analytics/git-version-control/git-fork-emphasis.png)
- [x] Forks
- [x] Pull Requests
- one-way
- another-way

### Git reference
- [basic commands cheatsheet](https://www.atlassian.com/ru/git/tutorials/atlassian-git-cheatsheet)
- [tutorial](https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository)

### Java platform overview <sup>10</sup>
- [ ] Java Platform definition
- [ ] Basic terms: JVM, JRE, JDK
- [ ] Installation
- [Oracle website](https://www.oracle.com/java/technologies/downloads/)
- [Adoptium](https://adoptium.net) builds
- your lovely package manager: `openjdk11`

### Simple app lifecycle <sup>10</sup>
- [ ] Sources
- sourcepath
- classpath
- [ ] Compiling
- compile errors
- [ ] Packaging
- jar tool
- [ ] Running
- classpath
- exceptions

### Maven build lifecycle <sup>20</sup>
- [ ] Minimum Directory layout
```shell
├── pom.xml
└── src
  └── main
      └── java
          ├── Application.java
          └── ConsolePrinter.java
```
- [ ] Build lifecycles: 3
- [ ] Lifecycle phases
- [ ] Plugins
- Default plugins
- Managing plugins with pom.xml

### Maven dependency management <sup>10</sup>
- [ ] Dependency artifacts: JARed classes, sources, javadocs
- [ ] Artifact repositories
- [ ] Artifact identifying
- [ ] Test dependencies vs Prod dependencies

### Maven reference
- [maven lifecycle](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html#lifecycle-reference)
- [maven cheatsheet](https://www.jrebel.com/blog/maven-cheat-sheet)

---

Java Application Development <sup>9</sup>
----------------------------

### IDEA Demo for developing <sup>0.2</sup>
- [ ] Project settings and structure: modules, sourcepath + classpath
- [ ] Workspace
- [ ] Views
- [ ] Running application with run configuration
- [ ] Git workflow
- [ ] Maven build

### Java Source Code Documenting <sup>0.1</sup>
- [ ] Source code layout
- [ ] Single-line comments
- [ ] Multi-line comments
- [ ] Downloading and working JavaDoc comments
- [ ] Downloading and working with sources

### Java Packages <sup>0.1</sup>
- [ ] Package: why?
- [ ] Package declaration
- [ ] Naming convention
- [ ] Import directive
- [ ] Encapsulation: why?
- [ ] Visibility modifiers

### Java Classes for Procedure Style <sup>0.2</sup>
- [ ] Class: why?
- [ ] Class declaration
- [ ] Naming convention
- [x] Dynamic class loading and `static` initialization section
- [ ] Encapsulation concept: behavior and state

### Method declaration <sup>0.4</sup>
- [ ] Method: why?
- [ ] Method declaration
- [ ] Naming convention
- [ ] Visibility modifiers
- [ ] Method body code block
- [ ] Methods overloading

---

### Local variables <sup>0.1</sup>
- [ ] Method arguments
- [ ] Method variables
- [ ] Returning values

### Method call <sup>0.2</sup>
- [ ] Dot notation
- [ ] Static import directive
- [ ] Call stack: why?

### Class variable declaration <sup>0.2</sup>
- [ ] Method vs Class variables: why?
- [ ] Declaration
- [ ] Visibility modifiers
- [ ] Initialization
- [ ] Default initialization values for class and method variables

### Variable declaration modifiers <sup>0.1</sup>
- [ ] `final` modifier for variables
- [ ] Local variables type inference with `var`

### Java Primitive types and its literals <sup>0.4</sup>
- [ ] byte
- [ ] int
- [ ] short
- [ ] long
- [ ] float
- [ ] double
- [ ] char
- [ ] boolean

---

### Type operators <sup>0.1</sup>
- [ ] Auto type casting
- [ ] type casting operator
- [ ] Method overloading recap

### Arithmetics operators <sup>0.1</sup>
- [ ] `+, -, *, /, %`
- [ ] `ArithmeticException` for integer types
- [ ] Typed operators: 1/3 vs 1./3
- [ ] `+` as String concatenation 

### Arithmetics type issues
- [ ] Overflow
- [ ] Precision loss

### Logical operators <sup>0.3</sup>
- [ ] Type-safe
- [ ] `&, |, !`
- [ ] Lazy and eager form: `&&, ||`
- [ ] `==, !=, <, <=, >, >=`
- [ ] Reference types equality issue: absence of `===` and `.equals()` instead

### Switching <sup>0.5</sup>
- [ ] Ternary operator
- [ ] `if`
- [ ] `switch` and its limitations

---

### Enums <sup>0.2</sup>
- [ ] Enumerated type concept: why?
- [ ] API
- [ ] Using with `switch`

### Looping <sup>0.5</sup>
- [ ] `for`
- [ ] `do` and `while`
- [ ] `break` and `continue` operators
- [ ] "foreach" loop for varargs

### Varargs <sup>0.1</sup>
- [ ] Why?
- [ ] Declaration
- [ ] Using
- [ ] Limitations

---

### Reference types <sup>0.4</sup>
- [ ] Custom (non-primitive) types
- Enum
- Interface
- Class
- [ ] Class as structure template
- [ ] Reference anatomy and `new` operator
- [ ] Stack and heap
- [ ] Garbage collection concept
- [ ] `null` literal value and NPE
- [ ] `final` issue with reference types
- [ ] Immutable types vs `final`

### Arrays <sup>0.3</sup>
- [ ] Declaration
- [ ] Initialization
- empty
- literals
- [ ] "Immutability" with size
- [ ] API: indexing operator, length
- [ ] Exceptions
- [ ] `foreach` loop
- [x] iteration loop with `for`

### Strings <sup>0.3</sup>
- [ ] Declaration
- [ ] Initialization with literal and constructor
- [ ] Strings equality: `==` vs `.equals()`
- [ ] `String` API
- [ ] Immutability

### Wrappers <sup>0.2</sup>
- [ ] Wrapper types: why?
- [ ] Wrapper types: referenced but immutable
- [ ] Wrappers API
- [ ] Autoboxing/unboxing and performance issue

### Immutability <sup>0.1</sup>
- [ ] Why immutability?

---

### Custom Type Objects <sup>0.5</sup>
- [ ] Objects: why?
- [ ] Class: why?
- [ ] Object/instance variable declaration scope
- [ ] Object/instance method declaration scope
- [ ] Encapsulation and visibility modifiers
- [ ] Encapsulated state accessors and mutators
- [ ] Immutable objects
- [ ] VO/DTO patterns

### Creating objects <sup>0.2</sup>
- [ ] Object creation with `new`
- [ ] Object state initialization with constructor
- [ ] Constructors overloading

### Polymorphism with interfaces and (abstract) classes <sup>0.3</sup>
- [ ] Polymorphism: why?
- [ ] Java implementation: how it looks in source code
- [ ] Interfaces
- [ ] Implementing interfaces

### DI *
- [ ] DI: Why?
- [ ] Constructor Injection implementation

---

### OOAD recap with JDBC example
- [ ] Encapsulation
- [ ] Polymorphism
- [ ] Creator DP
- [ ] Factory Method DP
- [ ] DI DP

### Defender methods concept <sup>0.1</sup>
- [ ] Defender methods: why?

### Inheritance with (abstract) classes concept <sup>0.5</sup>
- [ ] Inheritance: why?
- [ ] Java implementation: how it looks in source code
- [ ] Abstract classes
- [ ] Classes for code reuse
- [ ] `final` modifier

### `Object` type <sup>0.4</sup>
- [ ] `java.lang.Object` class as basic reference type
- [ ] All objects are polymophic: why?
- [ ] Equality: `==` vs `.equals()`
- [ ] `equals()` and `hashCode()` contract
- [ ] `toString()`

---

### Exception concept <sup>0.2</sup>
- [ ] Type information
- [ ] Object data information
- [ ] `throw` operator
- [ ] Methods call stack information

### Handling exceptions <sup>0.3</sup>
- [ ] creating exception instance
- [ ] `try` section
- [ ] `catch` section
- [ ] `finally` section

### Syntax sugar <sup>0.2</sup>
- [ ] multi-catch
- [ ] try-with-resources

### Exceptions type system <sup>0.3</sup>
- [ ] Built-in types
- [ ] Errors vs Exceptions
- [ ] Checked vs Runtime exceptions

---

### Generics <sup>0.1</sup>
- [ ] Generics: why?
- [ ] Generic class and method demo
- [x] Generic classes and interfaces
- [x] Generic methods

### Key Collections API overview <sup>0.3</sup>
- [ ] `Collection` API
- [ ] `Set` API and implementations
- [ ] `List` API  and implementations
- [ ] non-collection `Map` API and implementations
- [ ] `Object`'s methods used: `equals` and `hashCode` contract

### Collections API and iterating <sup>0.2</sup>
- [ ] `Iterator` and `for` loop
- [ ] `foreach`

### Lambda syntax overview <sup>0.2</sup>
- [ ] Declaring lambdas
- [ ] Compiler types inference
- [ ] Functional interface
- [ ] Method reference

### Stream API concept <sup>0.2</sup>
- [ ] Functions composition
- [ ] Terminal and non-terminal operations

---

Developing autotests with JUnit <sup>1</sup>
-------------------------------

### JUnit framework overview <sup>0.1</sup>
- [ ] Maven test dependency for JUnit5 Jupiter 
- [ ] JUnit is a Framework 
- [ ] Test class and methods
- [ ] Annotations
- [ ] Built-in Assertions

### Test design <sup>0.4</sup>
- [ ] Test Case and Test method naming
- [ ] Code execution path
- [ ] Input and State
- [ ] Fixture
- [ ] Test structure

### Fixture reuse <sup>0.1</sup>
- [ ] How many test instances?
- [ ] How to reuse fixture?
- [ ] JUnit test case lifecycle methods
- [x] Fixture Builders

### Testing alternate flows within tests <sup>0.2</sup>
- [ ] Test states
- failure
- error
- skipped (+assumes)
- [ ] JUnit5 `assertThrows`

### Advanced assertions <sup>0.1</sup>
- [ ] [JUnit assertions combinator `assertAll`](https://www.javaguides.net/2018/09/junit-5-assertall-example.html)
- [x] [Hamcrest matchers library](http://hamcrest.org/JavaHamcrest/tutorial)
- [x] [AssertJ fluent API library](https://assertj.github.io/doc/)

### Advanced JUnit <sup>0.1</sup>
- [x] Suites
- [Nested test classes](https://junit.org/junit5/docs/current/user-guide/#writing-tests-nested)
- [Test suites](https://junit.org/junit5/docs/current/user-guide/#running-tests-junit-platform-runner-test-suite)
- [Tags](https://junit.org/junit5/docs/current/user-guide/#writing-tests-tagging-and-filtering) [и отдельный запуск](https://junit.org/junit5/docs/current/user-guide/#running-tests-build-maven-filter-tags)
- [x] [Parameterized tests](https://junit.org/junit5/docs/current/user-guide/#writing-tests-parameterized-tests)

---

Docker for QA <sup>1</sup>
-------------

### Application overview <sup>0.2</sup>
- [ ] Application architecture
- DB
- backend
- API
- client
- [ ] Authentication
- [ ] Overview of [demo application](app.codegen/README.md)

### Docker overview <sup>0.2</sup>
- [ ] Docker: why?
- [ ] Image: why?
- [ ] Registry: why?
- [ ] Container: why?
- [ ] Containers vs VMs

### Docker Image <sup>0.2</sup>
- [ ] Images naming and tags
- [ ] `build`
- [ ] `ls`
- [ ] `pull`/`push`
- [ ] `rm`

### Docker container <sup>0.2</sup>
- [ ] Containers naming
- [ ] port mappings
- [ ] `ls`
- [ ] `run`
- [ ] `log`

### Configuration externalization <sup>0.1</sup>
- [ ] Externalization: why?
- [ ] How to externalize configuration: 3 patterns

### Orchestration <sup>0.1</sup>
- [ ] Orchestration: why?
- [ ] Primitive orchestration with docker-compose
```shell
cd app.codegen

docker-compose up --detach

docker-compose ls
docker-compose ps
docker-compose logs

docker-compose down
```

---

Java REST API Testing <sup>1</sup>
---------------------
### REST API description <sup>0.2</sup>
- [ ] [Swagger](https://swagger.io)
- [ ] [OpenAPI](https://ru.wikipedia.org/wiki/OpenAPI_(спецификация))

### REST intro
- [ ] REST request and response
- Method
- Params
- Headers
- Body
- Status / Error code
- [ ] HTTP methods
- for CRUD
- [x] [POST vs PUT](https://stackoverflow.com/questions/630453/what-is-the-difference-between-post-and-put-in-http)

### REST Assured <sup>0.4</sup>
- [ ] [Overview](https://rest-assured.io)
- [ ] [Best Practices](https://habr.com/ru/post/421005/)

### Retrofit <sup>0.4</sup>
- [x] [Overview](https://square.github.io/retrofit/)
- [x] [CRUD](https://guides.codepath.com/android/consuming-apis-with-retrofit)
- [x] [Domain objects vs JSON Schema](https://www.jsonschema2pojo.org) 
- [x] [Error Handling](https://futurestud.io/tutorials/retrofit-2-simple-error-handling)

### TestContainers
- [x] Manage containers directly from tests with [TestContainers](https://www.testcontainers.org)

---

Testing DB applications <sup>1</sup>
-----------------------

### Running App with external DB
- [ ] Externalizing App configuration for external DB
- [ ] Running containerized DB
- [ ] Running containerized App

### DBMS overview <sup>0.2</sup>
- [x] Application testing architecture
- [x] Test scopes
- [x] Testing stateful applications
- [x] Test fixture patterns

### SQL overview <sup>0.1</sup>
- [x] DDL vs DML
- [x] inserts
- [x] updates
- [x] selects
- [x] joins

### DB overview with IDEA
- [ ] DB client at IDEA
- [ ] Connecting
- [ ] Overview

### JDBC intro <sup>0.7</sup>
- [ ] Driver
- [ ] Connection
- [ ] Statement
- [ ] ResultSet
- [ ] Resource closing

---

Building CI/CD pipeline with GitLab <sup>1</sup> 
-----------------------------------

### CI/CD overview <sup>0.4</sup>
- [ ] [CI/CD pipeline overview](https://paper.dropbox.com/doc/Delivery-Pipeline-ci-cd-devops--BjFQrnzacCxT_5vhahCW~cFCAg-OBLCVRSkMek24U7IXIHbq)
- [ ] [GitLab concepts](https://docs.gitlab.com/ee/ci/)
- [ ] [Pipeline overview](https://docs.gitlab.com/ee/ci/pipelines/)

### GitLab CI pipeline developing overview <sup>0.2</sup>
- [ ] [Demo for `gitlab-ci.yml`](https://gitlab.com/demo-group67/demo-project/-/pipelines)
- [ ] Creating project and pipeline
- [ ] Pipeline definition overview
- [ ] Triggers

### GitLab CI pipeline running and monitoring <sup>0.4</sup>
- [ ] Running pipeline
- [ ] Run status
- [ ] Logs and troubleshooting

---

Командный проект <sup>3 часа, 1 неделя</sup>
----------------
Here you get both:
- [ ] Mandatory tasks
- [x] Optional tasks

### Given:
- All the skills and codebase you made yourself with previous practice
- [Java REST API backend codebase](https://github.com/eugene-krivosheyev/spring-petclinic-rest)
- [Spring application main configuration](https://github.com/eugene-krivosheyev/spring-petclinic-rest/blob/main/src/main/resources/application.properties)
- [Spring application configuration profile named `postgres`](https://github.com/eugene-krivosheyev/spring-petclinic-rest/blob/main/src/main/resources/application-postgres.properties) with default values
- [DDL схемы БД](https://github.com/eugene-krivosheyev/spring-petclinic-rest/tree/main/src/main/resources/db/postgres)
- [Maven build script](https://github.com/eugene-krivosheyev/spring-petclinic-rest/blob/main/pom.xml)
- [Docker image description](https://github.com/eugene-krivosheyev/spring-petclinic-rest/blob/main/Dockerfile)

### When attendees:
- [ ] Run backend application storing its data with PostgreSQL both dockerized
- [ ] Check database schema provisioning with any suitable DB client  
- [ ] Document run instructions with `README.md`
- [x] Implement run with `docker-compose.yml`
- [ ] Develop REST API autotests with quality criteria
- self-describing
- isolated
- coverage of CRUD main flows for core domain entities/resources
- [ ] Describe bugs found in backend business-logic with `FIXME.md`
- [x] Implement correct TO-BE scenarios as `@Disabled` auto-tests with `@DisplayName` and `/** Javadoc comments */` describing bugs found  
- [x] Fix bugs in backend java code
- [x] Develop GitLab build pipeline

### Then:
- [ ] Attendees push to `main` branch for code review
- [ ] Mentors make code review and give feedback with comments and points:
- Documented run instructions with `README.md`: 1 point
- Implement run with `docker-compose.yml`: 2 points
- Develop REST API autotests: 0.5 points for each `@Test`
- Describe bugs found in backend business-logic with `FIXME.md`: 0.5 points for each bug described
- Implement correct TO-BE scenarios: 0.5 points for each `@Test`
- Fix bugs in backend java code: 2 points for each bug fix
- Develop GitLab build pipeline: 3 points
