
*Notes from an improvised talk at [the IT Garage](https://twitter.com/TheITGarage), July 2015*

###### Lifecycle of a Bug Fix

Buildings have basic infrastructure concerns (e.g. plumbing, electrical, etc) that are independent of the purpose of the building. Software projects have similar infrastructure building blocks.

In this informal, free-form talk, we'll identify these infrastructure blocks, such as source-control. We'll begin with a terrifying example "we just hacked it in Production", and go from there.

###### Issue Tracker 
* given "bug X", how do we track the status of the work?
* [Issue tracking definition](https://en.wikipedia.org/wiki/Issue_tracking_system)
* [JIRA](https://en.wikipedia.org/wiki/JIRA)
* [GitHub](https://guides.github.com/features/issues/)
* [Mantis](https://en.wikipedia.org/wiki/Mantis_Bug_Tracker)

###### Source Control
* where is the definitive copy of the source code?
* [source/version definition](https://en.wikipedia.org/wiki/Revision_control)
* [Git](https://en.wikipedia.org/wiki/Git_(software))
* [Subversion](https://en.wikipedia.org/wiki/Apache_Subversion)
* [others](https://en.wikipedia.org/wiki/List_of_revision_control_software)

###### Build Tool 
* how do we compile, run unit tests, and generate deliverables? 
* [build tool definition](https://en.wikipedia.org/wiki/Build_automation)
* [Ant](https://en.wikipedia.org/wiki/Apache_Ant), [Gradle](https://en.wikipedia.org/wiki/Gradle), [Maven](https://en.wikipedia.org/wiki/Apache_Maven) for Java and JVM languages
* [Rake](https://en.wikipedia.org/wiki/Rake_(software)) in Ruby
* many others, depending on language

###### Unit testing
* in the spirit of double-ledger accounting, can we confirm our code works? 
* better yet, can we write a test **first** as a design contract/exploration
* [unit test reference](https://en.wikipedia.org/wiki/Unit_testing)
* [TDD reference](https://en.wikipedia.org/wiki/Test-driven_development)
* [JUnit](https://en.wikipedia.org/wiki/JUnit)

###### Acceptance testing
* can we confirm that our app works? (at the user level) 
* [Selenium](https://en.wikipedia.org/wiki/Selenium_(software))
* [Sikuli](http://www.sikuli.org/)
* [FitNesse](https://en.wikipedia.org/wiki/FitNesse)

###### Build Server (Continuous Integration Server)
* can we automate the build process via a dedicated agent?
* [Continuous Integration definition](https://en.wikipedia.org/wiki/Continuous_integration)
* [Martin Fowler's original article on CI](http://www.martinfowler.com/articles/continuousIntegration.html)
* [Jenkins](https://en.wikipedia.org/wiki/Jenkins_(software))
* [Travis CI](https://en.wikipedia.org/wiki/Travis_CI)

###### DevOps and tools
* [DevOps](https://en.wikipedia.org/wiki/DevOps)
* [Deployment environment](https://en.wikipedia.org/wiki/Deployment_environment) e.g. QA, UAT, Production
* [Virtual Machine](https://en.wikipedia.org/wiki/Virtual_machine)
* [Vagrant](https://en.wikipedia.org/wiki/Vagrant_(software))
* [Docker](https://en.wikipedia.org/wiki/Docker_(software))

