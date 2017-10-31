# WinformsCICD

Repository contains agenda of one day training Client Server Windows forms socks application 
that covers:
## Legend:
 - [TH] - Theoretical lecture about subject 
 - [HO] - Hands on, exercise covers theoretical 
 - [QA] - Questions and answers, general discussion about presented materials
 -
## Agenda
* Introduction (10 min)
	* Short introduction about me (5 min)
	* [QA] What use cases we should address during training (10 min)
	
* Setup environment (20 min)
* SCM tools and key best practices based on git and svn tools: (10 min)
   * [TH] branches how to use it and why (10 min)
   * [TH] svn vs git
   		* git core features (10 min)
   		* svn core feature (5 min)
   * [HO] git how to use it with gihub.com (5m)
   * [HO] svn how to use it with gihub.com (10m)

* Winforms demo application client/server based on socks protocol (15min)
	* [TH] Core features and typical client/server modules (10 min)
	* [QA] Discuss presented topics (5 min)
	
* Automated build system with Jenkins 
	* [TH] Introduction to Jenkins build system (10 min)
  	* [HO] Configure local jenkins environment (20 min)
    * [TH] Pipelines why and how to use them (10 min)
    * [HO] Simple Pipelines run batch script (10 min)
    * [TH] Pipelines as a code (5 min)
    * [HO] Compile Winforms demo application using Jenkins and batch script (10 min)
    * [QA] Discuss presented topics (5 min)

* Automated build and tests with MS Build
	* [TH] Introduction to MS Build (10 min)
    * [TH] Why to use it, best practices (5 min) 
    * [TH] Build C# solution using MS build (10 min)
    * [HO] Compile release/debug winforms demo application using MS Build command line (10min)
    * [HO] Compile release/debug winforms demo application using MS Build with Jenkins (10min)
 	* [QA] Discuss presented topics (5 min)
 	
* Unit tests
  	* [HT] Unit tests key definitions what they should address (10 min)
  	* [TH] Introduction to Nunit as a unit tests framework (10 min)
  	* [TH] Key features setup, teardown, tests sections (15 min)
    <!-- https://github.com/nunit/docs/wiki/NUnit-Documentation -->
    * [TH] Run tests from command line using Console Runner (15 min)
    <!-- https://github.com/nunit/docs/wiki/Console-Runner -->
    * [TH] Visual Studio integration Test Adapter (15 min) 
    <!-- https://github.com/nunit/docs/wiki/Visual-Studio-Test-Adapter 
    https://marketplace.visualstudio.com/items?itemName=NUnitDevelopers.NUnit3TestAdapter -->
    * [TH] Mocking code with FakeITEasy and NSubstitude (15 min)
    <!-- http://fakeiteasy.readthedocs.io/en/stable/quickstart/ 
    http://nsubstitute.github.io/help/getting-started/
    -->
    * [HO] Run demo prepared unit test (5 min)
    * [HO] Implement real life use case 1-2 unit tests (30 min)
    * [HO] Run/debug tests from commandline using Nunit3  (10 min)
    * [HO] Run/debug tests from Visual studio using NUnit3 Visual Studio Test Adapter (10 min)
    * [QA] Discuss presented topics (5 min)

* Functional and UI tests
	* [HT] Functional tests, key definitions and what they should address (10 min)
 	* [TH] Introduction to MS Coded UI Test Builder pros and cons (5 min) <!-- https://msdn.microsoft.com/en-us/library/dd286726.aspx 
     https://msdn.microsoft.com/en-us/library/dd286681(v=vs.100).aspx -->
 	* [TH] Introduction to White UI tests framework (5 min) <!-- http://white.teststack.net/docs/getting-started -->
	* [TH] White Key features (15 min)
    * [HO] Run demo UI test (10 min)
    * [HO] Implement real life use case 1-2 UI tests (30 min)
    * [QA] Discuss presented topics (5 min)

* Code coverage
	* [TH] Why to measure it and metrics (5 min)
	* [TH] Introduction to OpenCover and ReportGenerator (10 min)
	* [HO] Generate full html code coverage report (15 min)
	* [QA] Discuss presented topics (5 min)

