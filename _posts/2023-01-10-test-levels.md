---
layout: post
title: "Test Levels"
date: 2023-01-10 15:00:32 -0500
permalink:  test-levels
---
**Unit (component) Testing**

Anything that is separately testable i.e modules of code.  Developer is usually responsible for this level of testing.   When developers write the code, they write tests for that piece of code.  

**Integration Testing** 

Put the modules of code together.  Focuses on interactions between components or systems. 

2 types of Integration Testing:

-	**Component Integration** -- integration between components, usually performed by the developer.  After developer finishes tests on each unit or module, they will begin to test them together, testing the integration between them.  

-	**System Integration** -- large project that consists of many systems i.e front end, back end, database, web service.  Each area is considered a system. System testing is performed by the tester.  
 
**System Testing** 

Testing the entire system as a whole and try to find as many defects as possible.  Most of the testing that a tester does is system testing (not unit, integration, or acceptance testing).

<p>**Rule of thumb: Make the test environment correspond to the final production environment.  Testing for the application will be done in a similar environment as the production environment.  If the users will be using Android, perform testing with Android.  If the users will be on Wi-Fi, test the application on Wi-Fi.  </p>

**Acceptance Testing** 

Makes sure that the software performs correctly.  Usually done by the users or the stakeholders.  The users use the software and report back if they find any bugs.  An example of acceptance testing is Alpha and Beta testing.
    
- **Alpha Testing** -- bring customers to the company and make them test on site.
- **Beta Testing** -- have customers test the application at home
