# Software Development Career Plan


## Benefits of Career Progression Plan

* Increase software development efficiency and ROI
* Reduce bug rate and increase customer happiness
* Identify knowledge gaps in teams and across the organization
* Increase developer job satisfaction and retention

## Proficiency Levels

**Apprentice** - demonstrates a broad awareness of topics in a category; can perform work with some oversight

**Journeyman** - demonstrates practiced knowledge of topics in a category; can perform work with no oversight and can assist others

**Master** - subject-matter expert of the topics in a category; leads adoption and continuous improvement across the organization

## Skill Categories

**Automated Testing** - unit testing, integration testing, end-to-end testing, test-driven development

**Core** - algorithms, data structures, soft skills / professionalism

**Design Patterns** - fundamental and enterprise patterns

**Design Principles** - object-oriented programming principles, packaging principles, antipatterns, metrics, UX

**Development Practices** - code review, debugging, pair programming, refactoring, Scrum

**DevOps** - source control (git), continuous integration, continuous delivery


## Skill / Proficiency Matrix

|                | **Automated<br>Testing** | **Core** | **Design<br>Patterns** | **Design<br>Principles** | **Development<br>Practices** | **DevOps** |
| -------------: | :----------------------: | :------: | :--------------------: | :----------------------: | :--------------------------: | :--------: |
| **Apprentice** | [details](#automated-testing-apprentice) | [details](#core-apprentice) | [details](#design-patterns-apprentice) | [details](#design-principles-apprentice) | [details](#development-practices-apprentice) | [details](#devops-apprentice) |
| **Journeyman** | [details](#automated-testing-journeyman) | [details](#core-journeyman) | [details](#design-patterns-journeyman) | [details](#design-principles-journeyman) | [details](#development-practices-journeyman) | [details](#devops-journeyman) |
| **Master**     | -- | -- | -- | -- | -- | -- |


## Roles

* [Developer](./roles/developer.md)
* [Sr. Developer](./roles/senior_developer.md)
* [Architect](./roles/architect.md)
* [DevOps Specialist](./roles/devops_specialiest.md)

## <a name="automated-testing-apprentice"></a>Automated Testing (Apprentice)

The ability to automate tests is critical to being able to deliver software quickly without sacrificing an acceptable level of quality. Manual testing, including using a debugger to verify code is working, is slow and costly. Unit testing, in particular, enables developers to quickly add or modify code without the fear of unknowingly breaking existing functionality.

#### Learning Goals/Topics
- Unit Testing
- Test-Driven Development (TDD)
- Pinning/Characterization Tests
- Testing Doubles (stubs, mocks, spies)
- Code Coverage

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources

Suggested Books
- [ ] [The Art of Unit Testing (C#)](https://www.amazon.com/Art-Unit-Testing-examples/dp/1617290890/) 
- [ ] [Effective Unit Testing (Java)](https://www.amazon.com/Effective-Unit-Testing-guide-developers/dp/1935182579)

Suggested Blog Posts
- [ ] ['Writing Descriptive Test Names', Google Testing Blog](https://testing.googleblog.com/2014/10/testing-on-toilet-writing-descriptive.html)
- [ ] ['Don't Put Logic in Tests', Google Testing Blog](https://testing.googleblog.com/2014/07/testing-on-toilet-dont-put-logic-in.html) 
- [ ] ['Test Behaviors, Not Methods', Google Testing Blog](https://testing.googleblog.com/2014/04/testing-on-toilet-test-behaviors-not.html)
- [ ] ['Change Detector Tests Considered Harmful', Google Testing Blog](https://testing.googleblog.com/2015/01/testing-on-toilet-change-detector-tests.html) 
- [ ] ['The Way of Testivus', Artima Weblog](https://www.artima.com/weblogs/viewpost.jsp?thread=203994)
- [ ] ['An Introduction to Code Coverage', Atlassian](https://www.atlassian.com/continuous-delivery/software-testing/code-coverage)
- [ ] ['How much test coverage do I need? - The Testivus Answer', DeveloperTesting.com](http://www.developertesting.com/archives/month200705/20070504-000425.html)
  
#### Exercises
- [ ] ['Roman Numerals - Coding Dojo', Coding Dojo](http://codingdojo.org/kata/RomanNumerals/)

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Demonstrate the ability to get untested code under test before modifying or adding behavoirs 
- [ ] Demonstrate the ability to use TDD to complete feature development
- [ ] Explain the differences between different testing doubles (stubs, mocks, spies)
- [ ] Demonstrate the use of code coverage to find and fill testing gaps

</details>

## <a name="automated-testing-journeyman"></a>Automated Testing (Journeyman)

#### Learning Goals/Topics
- Acceptance Test-Driven Development (ATDD)
  - Gherkin
- Integration Testing
- End-to-End Testing
- Advanced Unit Testing Techniques

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources

Suggested Books
- [ ] [The Cucumber for Java Book: Behaviour-Driven Development for Testers and Developers](https://www.amazon.com/dp/1941222293)
- [ ] [Working Effectively with Legacy Code, Chapters 1-24](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)

Suggested Blog Posts
- [ ] ['What Makes a Good Test?', Google Testing Blog](https://testing.googleblog.com/2014/03/testing-on-toilet-what-makes-good-test.html)
- [ ] ['What Makes a Good End-to-End Test?', Google Testing Blog](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html)
- [ ] ['Test Behavior, Not Implementation'](https://testing.googleblog.com/2013/08/testing-on-toilet-test-behavior-not.html)
- [ ] ['Expect vs. Assert', Google Testing Blog](https://testing.googleblog.com/2008/07/tott-expect-vs-assert.html)
- [ ] ['Test Coverage', Martin Fowler Bliki](https://martinfowler.com/bliki/TestCoverage.html)
- [ ] ['Cobra effect', Wikipedia](https://en.wikipedia.org/wiki/Cobra_effect)
- [ ] [Test-Driven Development By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
- [ ] [How to Misuse Code Coverage](http://www.exampler.com/testing-com/writings/coverage.pdf)
- [ ] ['Don't Overuse Mocks', Google Testing Blog](https://testing.googleblog.com/2013/05/testing-on-toilet-dont-overuse-mocks.html)

Other
- [ ] Limit invariants to improve tests

#### Exercises
- [ ] [The Ray Tracer Challenge](https://www.amazon.com/Ray-Tracer-Challenge-Test-Driven-Renderer/dp/1680502719)

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Demonstrate the ability to create end-to-end tests using Cucumber or some equivalent ATDD tool

</details>

## <a name="core-apprentice"></a>Core (Apprentice)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Conceptual Blockbusting](https://www.amazon.com/Conceptual-Blockbusting-Guide-Better-Ideas/dp/0738205370)
- [ ] [The Clean Coder](https://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)
- [ ] [A Common-Sense Guide to Data Structures and Algorithms](https://www.amazon.com/Common-Sense-Guide-Data-Structures-Algorithms/dp/1680502441)

#### Training
- [ ] [HackerRank - Java Language Proficiency](https://www.hackerrank.com/domains/java)
- [ ] [The Design of Everyday Things](https://www.udacity.com/course/intro-to-the-design-of-everyday-things--design101)
- [ ] [Algorithms and Data Structures, PluralSight](https://www.pluralsight.com/courses/ads-part1)
- [ ] [Advent of Code, Day 19: An Elephant Named Joseph](https://adventofcode.com/2016/day/19)
  - [ ] Implement using array list
  - [ ] Implement using a linked list
  - [ ] Explain the trade-offs of the implementations

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Maintain a weekly mentorship for 3 months; track what was discussed/learned
- [ ] Complete "HackerRank - Java Language Proficiency" problems for the following sub-domains:
  - [ ] Introduction
  - [ ] Strings
  - [ ] BigNumber
  - [ ] Data Structures
  - [ ] Object Oriented Programming
  - [ ] Exception Handling
- [ ] Demonstrate the importance of setting capacity on a data structure when applicable

</details>

## <a name="core-journeyman"></a>Core (Journeyman)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources

Suggested Books
- [ ] [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850/)
- [ ] [Programming Pearls](https://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880)

#### Exercises
- [ ] Implement a Chip-8 Emulator

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] ...

</details>

## <a name="design-patterns-apprentice"></a>Design Patterns (Apprentice)

#### Learning Goals/Topics
- Types of Design Patterns (Creational, Structural, and Behavioral)
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
  <summary>Resources and Exercises</summary>
  
#### Resources

Suggested Books
- [ ] [Head First Design Patterns](https://www.amazon.com/Head-First-Design-Patterns-Brain-Friendly/dp/0596007124)

Suggested Blog Posts
- [ ] [The Monostate pattern](https://www.simplethread.com/the-monostate-pattern/)
- [ ] [Fluent Interface](https://martinfowler.com/bliki/FluentInterface.html)
- [ ] [Builder Pattern](https://www.geeksforgeeks.org/builder-design-pattern/)

Websites
- [ ] https://www.dofactory.com/net/design-patterns
- [ ] https://github.com/iluwatar/java-design-patterns
- [ ] https://www.javatpoint.com/design-patterns-in-java

#### Exercises
- [ ] [Gilded Rose Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata)
- [ ] [Design Patterns Library, PluralSight](https://www.pluralsight.com/courses/patterns-library)
- [ ] [StringBuilder Workshop](../exercises/string_builder_workshop.md)

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
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

#### Learning Goals/Topics
- Adapter
- Bridge
- Composite
- Facade
- Mediator
- Observer
- Proxy
- State
- Visitor

<details>
  <summary>Resources and Exercises</summary>
  
### Resources

Suggested Books
- [ ] [Agile Principles, Patterns, and Practices in C#](https://www.amazon.com/Agile-Principles-Patterns-Practices-C/dp/0131857258)

### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
### Professional Experience
- [ ] ...

</details>

## <a name="design-principles-apprentice"></a>Design Principles (Apprentice)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- [ ] [Don't Make Me Think Revisited](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515)
- [ ] ['Don't Repeat Yourself', Wikipedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- [ ] ['When Does DRY become ARID?', Jeremy Bytes Blog](https://jeremybytes.blogspot.com/2015/08/when-does-dry-become-arid.html)
- [ ] ['YAGNI', Martin Fowler Bliki](https://martinfowler.com/bliki/Yagni.html)
- [ ] [Your Constructors are Completely Irrational, The Code Whisperer Blog](https://blog.thecodewhisperer.com/permalink/your-constructors-are-completely-irrational)
- [ ] [Beware the Bloated Constructor, DaedTech Blog](https://daedtech.com/beware-the-bloated-constructor/)
- [ ] [How to Write Unmaintainable Code](https://www.se.rit.edu/~tabeec/RIT_441/Resources_files/How%20To%20Write%20Unmaintainable%20Code.pdf)

#### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] As part of a code review, identify a problem with poorly implemented constructor and suggest an alternative
- [ ] As part of a code review, suggest a better name for a method or variable
- [ ] ...

</details>

## <a name="design-principles-journeyman"></a>Design Principles (Journeyman)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Agile Principles, Patterns, and Practices in C#](https://www.amazon.com/Agile-Principles-Patterns-Practices-C/dp/0131857258)
  - [ ] Chapter 7, What is Agile Design?
  - [ ] Chapter 8, The Single-Responsibility Principle (SRP)
  - [ ] Chapter 9, The Open/Closed Principle (OCP)
  - [ ] Chapter 10, The Liskov Substitution Principle (LSP)
  - [ ] Chapter 11, The Dependency-Inversion Principle (DIP)
  - [ ] Chapter 12, The Interface Segregation Principle (ISP)
- [ ] [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052)
- [ ] ['Is Design Dead?', Martin Fowler Bliki](https://martinfowler.com/articles/designDead.html)
- [ ] ['Tony Hoare, Apologies and Retractions', Wikipedia](https://en.wikipedia.org/wiki/Tony_Hoare#Apologies_and_retractions)

#### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Identify code stratifaction problem in code review

</details>

## <a name="development-practices-apprentice"></a>Development Practices (Apprentice)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Extreme Programming Explained: Embrace Change](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0321278658)
- [ ] [The Cost and Benefits of Pair Programming](https://collaboration.csc.ncsu.edu/laurie/Papers/XPSardinia.PDF)
- [ ] [Why code reviews matter (and actually save time)](https://www.atlassian.com/agile/software-development/code-reviews)
- [ ] [Business Case for Better Software Practices](https://www.construx.com/resources/business-case-for-better-software-practices/)
- [ ] [20 Patterns to Watch For in Your Engineering Team](https://resources.gitprime.com/books/20-patterns/)
- [ ] [Scrum Guide](https://www.scrum.org/resources/scrum-guide)
- [ ] [Scrum@Scale Guide](https://www.scrumatscale.com/scrum-at-scale-guide/)

#### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Leave 10 comments across multiple code reviews that elicit code changes from the author (provide links to PRs)
- [ ] Complete an entire feature using pair programming
- [ ] Pass [Scrum Open Assessments](https://www.scrum.org/open-assessments)
  - [ ] Scrum Open
  - [ ] Product Owner Open
  - [ ] Developer Open

</details>

## <a name="development-practices-journeyman"></a>Development Practices (Journeyman)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Refactoring](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599)

#### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] ...

</details>

## <a name="devops-apprentice"></a>DevOps (Apprentice)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [DevOps Handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002)
- [ ] [Atlassian's Comparing Git Workflows article](https://www.atlassian.com/git/tutorials/comparing-workflows)
- [ ] [Atlassian's Gitflow Workflow article](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
- [ ] [Road to Continuous Deployment - Intuit](https://quickbooks-engineering.intuit.com/road-to-continuous-deployment-65bd03b985fc)

#### Exercises
- [ ] [Git Immersion](http://gitimmersion.com/lab_01.html)
- [ ] [Intro to DevOps, Udacity](https://www.udacity.com/course/intro-to-devops--ud611)
- [ ] [How to Use Git and Github, Udacity](https://www.udacity.com/course/how-to-use-git-and-github--ud775)

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] Setup a new Git repository and create the necessary branches for Gitflow
- [ ] Create a feature using Gitflow
- [ ] Create a release using Gitflow
- [ ] Create a hotfix using Gitflow
- [ ] Create a build plan in a CI/CD tool of your choice (e.g. Jenkins, Bamboo, GitLab, Azure DevOps) that does the following:
  - [ ] Triggers a build when a new branch is created on the remote server
  - [ ] Compiles the code on that branch
  - [ ] Executes unit tests against the compiled code
  - [ ] Attaches build artifacts to the build 
- [ ] Configure a Git service to require a code review to merge into the develop branch
- [ ] Configure a Git service to require a successful build to merge into the develop branch

</details>

## <a name="devops-journeyman"></a>DevOps (Journeyman)

<details>
  <summary>Resources and Exercises</summary>
  
#### Resources
- [ ] [Agile Principles, Patterns, and Practices in C#](https://www.amazon.com/Agile-Principles-Patterns-Practices-C/dp/0131857258)
  - [ ] Chapter 28, Principles of Package and Component Design

#### Exercises
- [ ] ...

</details>

<details>
  <summary>Professional Experience</summary>
  
#### Professional Experience
- [ ] ...

</details>
