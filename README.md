# Software Development Career Plan

This document is a collection of resources and ideas for accelerating skills development for software engineeers. While a lot of the skills are specific to object-oriented programming, there is plenty that isn't specific to any particular technology stack. It is not the intent that someone would read every book and work every exercise because:

  1. Different people learn by different methods
  1. There may be equivalent resources that people prefer to the ones listed here
  1. No one should ever be **done** learning

Instead, engineers are encouraged to work with a mentor to decide which skills and resources are going to be most useful.

#### Why should organizations have a career progression plan?

* Increase software development efficiency and ROI
* Reduce bug rate and increase customer happiness
* Identify knowledge gaps in teams and across the organization
* Increase developer job satisfaction and retention

## How is the plan implemented?

The plan consists of 3 levels of proficiency across 6 skill categories. These are used to create a skills/proficiency matrix which provides a suggested target proficiency for specific roles. This means that individuals in those respective roles aren't expected to have those proficiencies, but to be working toward them.

### Proficiency Levels

*Apprentice* - demonstrates a broad awareness of topics in a category; can perform work with some oversight

*Journeyman* - demonstrates practiced knowledge of topics in a category; can perform work with no oversight and can assist others

*Master* - subject-matter expert of the topics in a category; leads adoption and continuous improvement across the organization

### Skill Categories

*Automated Testing* - unit testing, integration testing, end-to-end testing, test-driven development

*Core* - algorithms, data structures, soft skills / professionalism

*Design Patterns* - fundamental and enterprise patterns

*Design Principles* - object-oriented programming principles, packaging principles, antipatterns, metrics, UX

*Development Practices* - code review, debugging, pair programming, refactoring, Scrum

*DevOps* - source control (git), continuous integration, continuous delivery

### Skill / Proficiency Matrix

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** | [details](#automated-testing-apprentice) | [details](#core-apprentice) | [details](#design-patterns-apprentice) | [details](#design-principles-apprentice) | [details](#development-practices-apprentice) | [details](#devops-apprentice) |
| **Journeyman** | [details](#automated-testing-journeyman) | [details](#core-journeyman) | [details](#design-patterns-journeyman) | [details](#design-principles-journeyman) | [details](#development-practices-journeyman) | [details](#devops-journeyman) |
| **Master**     | -- | -- | -- | -- | -- | -- |


## Roles

The tables below suggest different roles for a software development shop along with levels of competencies to target within each category.

### Developer

The goal of building the competencies below is to establish a baseline understanding of software development skills. 

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** |  X                       | X        | X                      | X                        | X                            | X          |
| **Journeyman** |                          |          |                        |                          |                              |            |
| **Master**     |                          |          |                        |                          |                              |            |

### Senior Developer

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** | X                        | X        | X                      | X                        | X                            | X          |
| **Journeyman** | X                        | X        |                        |                          | X                            |            |
| **Master**     |                          |          |                        |                          |                              |            |

### Architect

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** |  X                       | X        | X                      | X                        | X                            | X          |
| **Journeyman** |                          | X        | X                      | X                        |                              |            |
| **Master**     |                          |          |                        |                          |                              |            |

### DevOps Specialist

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** |                          |          |                        |                          | X                            | X          |
| **Journeyman** |                          |          |                        |                          |                              |            |
| **Master**     |                          |          |                        |                          |                              |            |

### Senior DevOps Specialist

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** |                          |        X |                        |                          | X                            | X          |
| **Journeyman** |                          |          |                        |                          | X                            | X          |
| **Master**     |                          |          |                        |                          |                              |            |

## <a name="automated-testing-apprentice"></a>Automated Testing (Apprentice)

The ability to automate tests is critical to being able to deliver software quickly without sacrificing an acceptable level of quality. Manual testing, including using a debugger to verify code is working, is slow and costly. Unit testing, in particular, enables developers to quickly add or modify code without the fear of unknowingly breaking existing functionality.

#### Learning Goals/Topics
- Unit Testing
- Test-Driven Development (TDD)
- Pinning/Characterization Tests
- Testing Doubles (stubs, mocks, spies)
- Code Coverage

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [The Art of Unit Testing (C#)](https://www.amazon.com/Art-Unit-Testing-examples/dp/1617290890/) 
- [ ] [Effective Unit Testing (Java)](https://www.amazon.com/Effective-Unit-Testing-guide-developers/dp/1935182579)

#### Suggested Blog Posts
- [ ] ['Writing Descriptive Test Names', Google Testing Blog](https://testing.googleblog.com/2014/10/testing-on-toilet-writing-descriptive.html)
- [ ] ['Don't Put Logic in Tests', Google Testing Blog](https://testing.googleblog.com/2014/07/testing-on-toilet-dont-put-logic-in.html) 
- [ ] ['Test Behaviors, Not Methods', Google Testing Blog](https://testing.googleblog.com/2014/04/testing-on-toilet-test-behaviors-not.html)
- [ ] ['Change Detector Tests Considered Harmful', Google Testing Blog](https://testing.googleblog.com/2015/01/testing-on-toilet-change-detector-tests.html) 
- [ ] ['The Way of Testivus', Artima Weblog](https://www.artima.com/weblogs/viewpost.jsp?thread=203994)
- [ ] ['An Introduction to Code Coverage', Atlassian](https://www.atlassian.com/continuous-delivery/software-testing/code-coverage)
- [ ] ['How much test coverage do I need? - The Testivus Answer', DeveloperTesting.com](http://www.developertesting.com/archives/month200705/20070504-000425.html)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ['Roman Numerals - Coding Dojo', Coding Dojo](http://codingdojo.org/kata/RomanNumerals/)

</details>

<details>
  <summary>Milestones</summary>

- [ ] Demonstrate the ability to get untested code under test before modifying or adding behavoirs 
- [ ] Demonstrate the ability to use TDD to complete feature development
- [ ] Explain the differences between different testing doubles (stubs, mocks, spies)
- [ ] Demonstrate the use of code coverage to find and fill testing gaps
- [ ] Explain common automated testing acronyms and patterns (A.A.A., F.I.R.S.T., Red-Green-Refactor)

</details>

## <a name="automated-testing-journeyman"></a>Automated Testing (Journeyman)

Developers need to be able to understand how their automated tests are directly linked to business value. Acceptance Test-Driven Development leads the developer to create their tests in a domain language that should be readable by non-technical resources. Also, integration and end-to-end tests can be used to validate automated deployments, ensuring an effective delivery pipeline that enables faster delivery of business value.

#### Learning Goals/Topics
- Acceptance Test-Driven Development (ATDD)
  - Gherkin
- Integration Testing
- End-to-End Testing
- Advanced Unit Testing Techniques

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [The Cucumber for Java Book: Behaviour-Driven Development for Testers and Developers](https://www.amazon.com/dp/1941222293)
- [ ] [Working Effectively with Legacy Code, Chapters 1-24](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)

#### Suggested Blog Posts
- [ ] ['What Makes a Good Test?', Google Testing Blog](https://testing.googleblog.com/2014/03/testing-on-toilet-what-makes-good-test.html)
- [ ] ['What Makes a Good End-to-End Test?', Google Testing Blog](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html)
- [ ] ['Test Behavior, Not Implementation'](https://testing.googleblog.com/2013/08/testing-on-toilet-test-behavior-not.html)
- [ ] ['Expect vs. Assert', Google Testing Blog](https://testing.googleblog.com/2008/07/tott-expect-vs-assert.html)
- [ ] ['Test Coverage', Martin Fowler Bliki](https://martinfowler.com/bliki/TestCoverage.html)
- [ ] ['Cobra effect', Wikipedia](https://en.wikipedia.org/wiki/Cobra_effect)
- [ ] [Test-Driven Development By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
- [ ] [How to Misuse Code Coverage](http://www.exampler.com/testing-com/writings/coverage.pdf)
- [ ] ['Don't Overuse Mocks', Google Testing Blog](https://testing.googleblog.com/2013/05/testing-on-toilet-dont-overuse-mocks.html)

#### Other
- [ ] Limit invariants to improve tests

</details>

<details>
  <summary>Exercises</summary>

- [ ] [The Ray Tracer Challenge](https://www.amazon.com/Ray-Tracer-Challenge-Test-Driven-Renderer/dp/1680502719)

</details>

<details>
  <summary>Milestones</summary>
  
- [ ] Demonstrate the ability to break down requirements into Gherkin syntax that can be used for automation
- [ ] Demonstrate the ability to create end-to-end tests using Cucumber or some equivalent ATDD tool
- [ ] Demonstrate the ability to create integration tests that verify interactions between to separately deployed systems (e.g. API and database)
- [ ] Demonstrate the ability to limit invariants in tests and explain how it can improve test quality
- [ ] Explain how cyclomatic complexity can be used to evaluate the quality of automated tests
- [ ] Explain the use and misuse of code coverage tools
- [ ] Demonstrate the ability to code review automated tests; identify good qualities and suggest improvements
- [ ] Explain the testing pyramid and how to decide home much of each testing type (unit, intergration, end-to-end) is necessary

</details>

## <a name="core-apprentice"></a>Core (Apprentice)

While most developers won't need to implement data structures or complex algorithms in their day-to-day development tasks, an understanding of how the tools they use daily work enables them to make better decisions and, also, reason about what may be going wrong.

#### Learning Goals/Topics
- Algorithms and Data Structures
- Problem Solving
- Professionalism

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Conceptual Blockbusting](https://www.amazon.com/Conceptual-Blockbusting-Guide-Better-Ideas/dp/0738205370)
- [ ] [The Clean Coder](https://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)
- [ ] [A Common-Sense Guide to Data Structures and Algorithms](https://www.amazon.com/Common-Sense-Guide-Data-Structures-Algorithms/dp/1680502441)
- [ ] [Code: The Hidden Language of Computer Hardware and Software](https://www.amazon.com/Code-Language-Computer-Hardware-Software/dp/0735611319)

#### Online Training
- [ ] [Algorithms and Data Structures, PluralSight](https://www.pluralsight.com/courses/ads-part1)

</details>

<details>
  <summary>Exercises</summary>

- [ ] [StringBuilder Workshop](./exercises/string_builder_workshop.md)
- [ ] [HackerRank - Java Language Proficiency](https://www.hackerrank.com/domains/java)
- [ ] [Advent of Code, Day 19: An Elephant Named Joseph](https://adventofcode.com/2016/day/19)
  - [ ] Implement using array list
  - [ ] Implement using a linked list
  - [ ] Explain the trade-offs of the implementations

</details>

<details>
  <summary>Milestones</summary>
  
- [ ] Maintain a weekly mentorship for 3 months; keep a log of what was discussed/learned
- [ ] Demonstrate the ability to select and use the best data structures in the current tech stack
  - [ ] Explain the tradeoffs between an array and a linked list
  - [ ] Explain the difference between a stack and a queue
  - [ ] Explain the implementation of commonly used data structures in the current tech stack
  
</details>

## <a name="core-journeyman"></a>Core (Journeyman)

Performance problems and memory leaks aren't something that developers generally have to deal with everyday. However, having the skills in-house to deal with these complex issues is far cheaper than paying a consultant to quickly diagnose and resolve a problem that has end users in a panic.

#### Learning Goals/Topics
- Algorithms and Data Structures
- Bitwise Operators
- Advanced Debugging
  - Memory Profiling
  - Performance Profiling

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/)
- [ ] [Programming Pearls](https://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880)

</details>

<details>
  <summary>Exercises</summary>

- [ ] Implement a Chip-8 Emulator

</details>

<details>
  <summary>Milestones</summary>
  
- [ ] ...

</details>

## <a name="design-patterns-apprentice"></a>Design Patterns (Apprentice)

In the relatively short history of software development, common design problems have emerged. As a result, there is a collection of common solutions to a lot of these problems exist, known as design patterns. Awareness of these patterns and the problems they solve will help developers better understand the libraries and frameworks they use. It also makes the problems these patterns solve more visible and, thus, less likely to introduced by developers. Finally, the names of these solutions provide a common vocabulary that developers can use to communicate complex ideas quickly, saving more time for writing code.

#### Learning Goals/Topics
- Types of Design Patterns
  - Creational
  - Structural
  - Behavioral
- Design Patterns
  - Adapter
  - Builder
  - Command
  - Factory
  - Fluent Interface
  - Null Object
  - Monostate
  - Repository
  - Singleton
  - Strategy
  - Template Method

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Head First Design Patterns](https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly/dp/0596007124)

#### Suggested Blog Posts
- [ ] [The Monostate pattern](https://www.simplethread.com/the-monostate-pattern/)
- [ ] [Fluent Interface](https://martinfowler.com/bliki/FluentInterface.html)
- [ ] [Builder Pattern](https://www.geeksforgeeks.org/builder-design-pattern/)

#### Websites
- [ ] https://www.dofactory.com/net/design-patterns
- [ ] https://github.com/iluwatar/java-design-patterns
- [ ] https://www.javatpoint.com/design-patterns-in-java

</details>

<details>
  <summary>Exercises</summary>

- [ ] [Gilded Rose Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata)
- [ ] [Design Patterns Library, PluralSight](https://www.pluralsight.com/courses/patterns-library)
- [ ] [StringBuilder Workshop](./exercises/string_builder_workshop.md)

</details>

<details>
  <summary>Milestones</summary>
  
- [ ] Describe the different categories of patterns: creational, structural, and behavioral
- [ ] Identify design patterns in the tech stack (language, libraries, frameworks) used in projects you are a contributor
- [ ] Appropriately apply the abstract factory pattern in a project
- [ ] Appropriately apply the factory method pattern in a project
- [ ] Appropriately apply the fluent builder pattern in a project, explain which part is fluent interface and which is builder
- [ ] Appropriately apply the monostate pattern in a project
- [ ] Appropriately apply, or identify the application of, the adapter pattern in a project
- [ ] Appropriately apply the facade pattern in a project
- [ ] Appropriately apply the template method pattern in a project
- [ ] Appropriately apply, or identify the application of, the iterator pattern in a project
- [ ] Appropriately apply, or identify the application of, the observer pattern in a project
- [ ] Appropriately apply, or identify the application of, the composite pattern in a project
- [ ] Appropriately apply the state pattern in a project
- [ ] Appropriately apply, or identify the application of, the proxy pattern in a project

</details>

## <a name="design-patterns-journeyman"></a>Design Patterns (Journeyman)

Architectural patterns describe common solutions to architectural problems like scalability, performance, reliability, and many more. Understanding the patterns help developers to make informed decisions about how their changes fit into the big picture. Architectural patterns are similar to design patterns, but differ in scope. Also, some of the less common, and more complex, design patterns are good to understand and can expand problem solving capabilities for developers.

#### Learning Goals/Topics
- Architectural Patterns
  - API Gateway
  - Circuit Breaker
  - Event Sourcing
  - Eventual Consistency
  - Microservices
- Design Patterns
  - Bridge
  - Composite
  - Facade
  - Mediator
  - Observer
  - Proxy
  - State
  - Visitor

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Building Microservices: Designing Fine-Grained Systems](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358)
- [ ] [Cloud Native Patterns: Designing change-tolerant software](https://www.amazon.com/Cloud-Native-Designing-change-tolerant-software/dp/1617294292)
- [ ] [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

- [ ] ...

</details>

## <a name="design-principles-apprentice"></a>Design Principles (Apprentice)

Design principles are a collection of industry wisdom and best practices that help developers create code that is easy to build upon and change. UX principles provide developers the ability to better empathize with end-users and produce solutions that are more intuitive and useful.

#### Learning Goals/Topics
- Design Principles
  - DRY
  - SOLID
  - YAGNI
- Temporal Coupling
- Law of Demeter
- UX Principles

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- [ ] [Don't Make Me Think Revisited](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515)

#### Suggested Blog Posts
- [ ] ['Don't Repeat Yourself', Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- [ ] ['When Does DRY become ARID?', Jeremy Bytes Blog](https://jeremybytes.blogspot.com/2015/08/when-does-dry-become-arid.html)
- [ ] ['YAGNI', Martin Fowler Bliki](https://martinfowler.com/bliki/Yagni.html)
- [ ] [Your Constructors are Completely Irrational, The Code Whisperer Blog](https://blog.thecodewhisperer.com/permalink/your-constructors-are-completely-irrational)
- [ ] [Beware the Bloated Constructor, DaedTech Blog](https://daedtech.com/beware-the-bloated-constructor/)

#### Other
- [ ] [How to Write Unmaintainable Code](https://www.se.rit.edu/~tabeec/RIT_441/Resources_files/How%20To%20Write%20Unmaintainable%20Code.pdf)
- [ ] [The Design of Everyday Things](https://www.udacity.com/course/intro-to-the-design-of-everyday-things--design101)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

- [ ] As part of a code review, suggest a better name for a method or variable
- [ ] Explain S.O.L.I.D. principles

</details>

## <a name="design-principles-journeyman"></a>Design Principles (Journeyman)

#### Learning Goals/Topics
- Code Stratification
- Design Principles
  - GRASP
- Packaging and Component Design Principles
  - Reuse/Release Equivalence Principle
  - Common Reuse Principle
  - Common Closure Principle
  - Acyclic Dependencies Principle
  - Stable Dependencies Principle
  - Stable Abstractions Principle
  
<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Agile Principles, Patterns, and Practices in C#](https://www.amazon.com/Agile-Principles-Patterns-Practices-C/dp/0131857258)
- [ ] [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052)

#### Suggested Blog Posts
- [ ] ['Is Design Dead?', Martin Fowler Bliki](https://martinfowler.com/articles/designDead.html)
- [ ] ['Tony Hoare, Apologies and Retractions', Wikipedia](https://en.wikipedia.org/wiki/Tony_Hoare#Apologies_and_retractions)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

- [ ] Demonstrate the ability to identify and correct code stratifaction problems
- [ ] Explain General Responsibility Assignment Software Patterns/Principles (GRASP)
- [ ] Demonstrate an understanding of Package and Component Design
  - [ ] Explain the Reuse/Release Equivalence Principle
  - [ ] Explain the Common Reuse Principle
  - [ ] Explain the Common Closure Principle
  - [ ] Explain the Acyclic Dependencies Principle
  - [ ] Explain the Stable Dependencies Principle
  - [ ] Explain the Stable Abstractions Principle

</details>

## <a name="development-practices-apprentice"></a>Development Practices (Apprentice)

#### Learning Goals/Topics
- Agile Development
  - Extreme Programming
  - Scrum
- Code Review
- Coding Standards
- Pair Programming

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Extreme Programming Explained: Embrace Change](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0321278658)
- [ ] [20 Patterns to Watch For in Your Engineering Team](https://resources.gitprime.com/books/20-patterns/)
- [ ] [Scrum Guide](https://www.scrum.org/resources/scrum-guide)
- [ ] [Scrum@Scale Guide](https://www.scrumatscale.com/scrum-at-scale-guide/)

#### Suggested Blog Posts
- [ ] [Why code reviews matter (and actually save time)](https://www.atlassian.com/agile/software-development/code-reviews)x

#### Suggested Whitepapers
- [ ] [The Cost and Benefits of Pair Programming](https://collaboration.csc.ncsu.edu/laurie/Papers/XPSardinia.PDF)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

- [ ] Leave 10 comments across multiple code reviews that elicit code changes from the author (provide links to PRs)
- [ ] Complete an entire feature using pair programming
- [ ] Pass [Scrum Open Assessments](https://www.scrum.org/open-assessments)
  - [ ] Scrum Open
  - [ ] Product Owner Open
  - [ ] Developer Open

</details>

## <a name="development-practices-journeyman"></a>Development Practices (Journeyman)

#### Learning Goals/Topics
- Emergent Design
- Refactoring

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Refactoring](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

</details>

## <a name="devops-apprentice"></a>DevOps (Apprentice)

#### Learning Goals/Topics
- Build Pipelines
- Configuration as Code
- Release Frequency
- Requirements Traceability
- Trunk-Based Development
- Static Code Analysis

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
- [ ] [DevOps Handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002)

#### Suggested Blog Posts
- [ ] [Atlassian's Comparing Git Workflows article](https://www.atlassian.com/git/tutorials/comparing-workflows)
- [ ] [Atlassian's Gitflow Workflow article](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- [ ] [Road to Continuous Deployment - Intuit](https://quickbooks-engineering.intuit.com/road-to-continuous-deployment-65bd03b985fc)

#### Suggested Websites
- [ ] [Trunk Based Development](https://trunkbaseddevelopment.com/)

</details>

<details>
  <summary>Exercises</summary>

- [ ] [Git Immersion](http://gitimmersion.com/lab_01.html)
- [ ] [Intro to DevOps, Udacity](https://www.udacity.com/course/intro-to-devops--ud611)
- [ ] [How to Use Git and Github, Udacity](https://www.udacity.com/course/how-to-use-git-and-github--ud775)

</details>

<details>
  <summary>Milestones</summary>

- [ ] Demonstrate the ability to create a CI pipeline in one or more tools (e.g. Jenkins, BitBucket Pipelines, Azure DevOps, GitLab, Travis CI)

</details>

## <a name="devops-journeyman"></a>DevOps (Journeyman)

#### Learning Goals/Topics
- Blue-Green Deployments
- Environments as Code
- Ephemeral Environments

<details>
  <summary>Resources</summary>

#### Suggested Books
- [ ] [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)

#### Suggested Blog Posts
- [ ] [State of DevOps](https://puppet.com/blog-tags/state-devops)

</details>

<details>
  <summary>Exercises</summary>

- [ ] ...

</details>

<details>
  <summary>Milestones</summary>

- [ ] ...

</details>
