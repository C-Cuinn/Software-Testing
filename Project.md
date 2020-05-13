# Software-Testing
Software Testing 

Prepared by: Ciaran Quinn G00361840
12/05/2020

Index

 1.0 INTRODUCTION.
  This document will describe and track the testing of the game "Pixel Wizard" as layed out in the brief distributed to us by the games 
  creater and developer for the 2020 Software testing project. It will document every aspect of the testing process in necessary depth.
  The Game being tested is a 2D Castlevania-esque side scrolled with exploration elements in line with those of
  The Elder Scrolls : Skyrim,
  Salt and Sanctuary,
  Dark Souls.
  
 2.0 OBJECTIVES AND TASKS.
  The objective of this testing program is to ensure the game is of quality and meets all relevant standards in accordance to GSA   
  (Gaming Standards Association) protocols and other relevant standards : 
 
 A.G2S MESSAGE PROTOCOL V3.1
 
 B.S2S MESSAGE PROTOCOL V2.0
 
 C.GDS NOTE ACCEPTOR COMMUNICATIONS PROTOCOL V1.4
  
 D.PKG MANIFEST FILE FORMAT V1.1
 
 E.GSA POINT-TO-POINT WEBSOCKET TRANSPORT SPECIFICATION V2.0
 
 F.GDS PERIPHERAL MANIFEST FILE FORMAT V1.0
 
 G.PLAYER USER INTERFACE STANDARD V1.1
  
 H.GSAEGM MEDIA DISPLAY INTERFACE PROTOCOL V3.1
  
 I.SSI SIMPLE SYSTEM INTERFACE V1.1
  
 J.GSA THIRD PARTY GAME INTERFACE V1.0
 
 The interpersonal comunications will be handled by microsoft teams .
 
 Issue tracking, progress tracking and roles will be tracked on Github with a backup of this information publicly displayed on Trello.
 ________________________________________________________________
 2.1 Objectives.
 The objectives of this testing phase will be to ensure adherence to the GSA standards and guidelines. It will focus on all testable
 aspects of the game such as design, performance, accessibilty and user friendlyness.
 The testing will primarily revolve around quality assurance and the pursuit of high quality thoroughly tested,and  fully functional end   product. 
 The Interfaces will be tested to assure that they conform to the standards layed out in the PUIS V1.1.
 
 2.2 Tasks.
 
 3.0 Scope.
 
 4.0 Testing Strategy.
 
 4.1 Unit Testing.
 
 4.2 System and Integration Testing.
 
 4.3 Performance and Stress Testing.
 
 4.4 User Acceptance Testing.
 
 4.5 Batch Testing.
 
 4.6 Automated Regression Testing.
 
 4.7 Beta Testing.
 
 5.0 Hardware Requirements.
 The hardware requirments for this will be based off my expierence with similar games and the games listed in the brief of which i have
 had previous experience through either playing them myself or by in depth research conducted in pursuit of this information.
  ________________________________________________________________

 Minumim Specfications : 
 
 OS : Windows : XP/Vista/7/8/10 ,Temple OS
 
 Graphics : GTX 970
 
 CPU : 2.2GHz Dual Core
 
 Memory : 4GB RAM
 
 Storage : 50GB free space
 
 Reccomended Specifications
 
 OS : Windows 10, Temple OS
 
 Graphics : GTX 3080 TI super
 
 CPU : 5.3GHz 10core 20t 
 
 Storage : 500GB free space
 
 ________________________________________________________________

 
 6.0 Environment Requirements.
 
 6.1 Main Frame.
 
 6.2 Workstation.
 
 7.0 Test Schedule.
 
 8.0 Control Procedures.
 
 9.0 Features to Be Tested.
 GUI : 
     All buttons should be tested to ensure that they do what they are supposed to 99.999% of the time.
     All sliders (Volume,Gamma,etc) should modify the relevent values in a proportial and intuative way.
     Menus should load quickly with little to no slowdown or latency.
     Menus should be responsive and clearly labeled.
     
 GamePlay : 
     The map and relevant areas should be tested for exploits such as "Out-of-bounds" glitches .
     Loading zones/transition zones should trigger when interacted with in an intuitive way.
     
 
 10.0 Features Not to Be Tested.
 
 11.0 Resources/Roles & Responsibilities.
 
 12.0 Schedules.
 
 13.0 Significantly Impacted Departments.
 
 14.0 Dependencies.
 
 15.0 Risks/Assumptions.
 
 16.0 Tools.
 The main tools to be used for this testing project are :
 
Ranorex : An all-in-one tool for test automation. Ranorex is easy for beginners with a codeless click-and-go interface, but powerful for automation experts with a full IDE for C# or VB.NET, and open APIs.
Functional UI and end-to-end testing on desktop, web, and mobile.
Cross-browser testing.
SAP, ERP, Delphi and legacy applications.
Run tests locally or remotely, in parallel or distribute on a Selenium Grid.
Robust reporting.
Ranorex integrates with leading solutions like Git, TFS, Jenkins, Bamboo, Bugzilla, SpecFlow, NeoLoad, TestRail and more for a complete testing toolchain.

TestCraft : A codeless Selenium test automation platform. The revolutionary AI technology and unique visual modeling allows for faster test creation and execution while eliminating test maintenance overhead. Testers create fully automated test scenarios without coding. Customers find bugs faster, release more frequently, integrate with CI/CD and improve overall quality of their digital products.
No programming skills required. Leverage manual testers’ business knowledge and allow them to create automated test scenarios
Substantially reduce maintenance costs. Scripts are automatically adjusted to change due to our AI mechanism.
Selenium based. Quickly integrate and leverage modules developed by the community
Provides immediate time to value. Easy to master.

Bugzilla : A leading Bug Tracking tool widely used by many organizations for quite some time now. It is very simple to use, web-based interface. It is completely open sourced and is free to use.
 
 17.0 Approvals.
 
1.0 INTRODUCTION
A brief summary of the product being tested. Outline all the functions at a high level.

2.0 OBJECTIVES AND TASKS

2.1 Objectives
Describe the objectives supported by the Master Test Plan, eg., defining tasks and responsibilities,
vehicle for communication, document to be used as a service level agreement, etc.

2.2 Tasks
List all tasks identified by this Test Plan, i.e., testing, post-testing, problem reporting, etc.

3.0 SCOPE
General
This section describes what is being tested, such as all the functions of a specific product, its existing
interfaces, integration of all functions.
Tactics
List here how you will accomplish the items that you have listed in the "Scope" section. For
example, if you have mentioned that you will be testing the existing interfaces, what would be the
procedures you would follow to notify the key people to represent their respective areas, as well as
allotting time in their schedule for assisting you in accomplishing your activity?

4.0 TESTING STRATEGY
Describe the overall approach to testing. For each major group of features or feature combinations,
specify the approach which will ensure that these feature groups are adequately tested. Specify the
major activities, techniques, and tools which are used to test the designated groups of features.
The approach should be described in sufficient detail to permit identification of the major testing
tasks and estimation of the time required to do each one. 

4.1 Unit Testing
Definition:
Specify the minimum degree of comprehensiveness desired. Identify the techniques which will be
used to judge the comprehensiveness of the testing effort (for example, determining which
statements have been executed at least once). Specify any additional completion criteria (for
example, error frequency). The techniques to be used to trace requirements should be specified.
Participants:
List the names of individuals/departments who would be responsible for Unit Testing.
Methodology:
Describe how unit testing will be conducted, including a description of tests to be carried out. Who
will write the test scripts for the unit testing, what would be the sequence of events of Unit Testing
and how will the testing activity take place?

4.2 System and Integration Testing
Definition:
List what is your understanding of System and Integration Testing for your project.
Participants:
Who will be conducting System and Integration Testing on your project? List the individuals that will
be responsible for this activity.
Methodology:
Describe how System & Integration testing will be conducted, including a description of tests to be
carried out Who will write the test scripts for the unit testing, what would be sequence of events of
System & Integration Testing, and how will the testing activity take place?

4.3 Performance and Stress Testing
Definition:
List what is your understanding of Stress Testing for your project.
Participants:
Who will be conducting Stress Testing on your project? List the individuals that will be responsible
for this activity.
Methodology:
Describe how Performance & Stress testing will be conducted, including a description of tests to be
carried out Who will write the test scripts for the testing, what would be sequence of events of
Performance & Stress Testing, and how will the testing activity take place? 

4.4 User Acceptance Testing
Definition:
The purpose of acceptance test is to confirm that the system is ready for operational use. During
acceptance test, end-users (customers) of the system compare the system to its initial requirements.
Participants:
Who will be responsible for User Acceptance Testing? List the individuals' names and responsibility.
Methodology:
Describe how the User Acceptance testing will be conducted, including a description of tests to be
carried out Who will write the test scripts for the testing, what would be sequence of events of User
Acceptance Testing, and how will the testing activity take place?

4.5 Batch Testing

4.6 Automated Regression Testing
Definition:
Regression testing is the selective retesting of a system or component to verify that modifications
have not caused unintended effects and that the system or component still works as specified in the
requirements.
Participants:
Methodology:

4.7 Beta Testing Participants:
Methodology:

5.0 TEST SCHEDULE
Include test milestones identified in the Software Project Schedule as well as all item transmittal
events.
Define any additional test milestones needed. Estimate the time required to do each testing task.
Specify the schedule for each testing task and test milestone. For each testing resource (that is,
facilities, tools, and staff), specify its periods of use.

6.0 CONTROL PROCEDURES
Problem Reporting
Document the procedures to follow when an incident is encountered during the testing process. If a
standard form is going to be used, attach a blank copy as an "Appendix" to the Test Plan. In the
event you are using an automated incident logging system, write those procedures in this section.
Change Requests
Document the process of modifications to the software. Identify who will sign off on the changes
and what would be the criteria for including the changes to the current product. If the changes will
affect existing programs, these modules need to be identified.

7.0 FEATURES TO BE TESTED
Identify all software features and combinations of software features that will be tested.

8.0 FEATURES NOT TO BE TESTED
Identify all features and significant combinations of features which will not be tested and the
reasons.

9.0 RESOURCES/ROLES & RESPONSIBILITIES
Specify the staff members who are involved in the test project and what their roles are going to be
(for example, Mary Brown (User) compile Test Cases for Acceptance Testing). Identify groups
responsible for managing, designing, preparing, executing, and resolving the test activities as well as
related issues. Also identify groups responsible for providing the test environment. These groups
may include developers, testers, operations staff, testing services, etc.

10.0 SCHEDULES
Identify the deliverable documents. You can list the following documents:
- Test Plan
- Test Cases
- Test Incident Reports
- Test Summary Reports

11.0 RISKS/ASSUMPTIONS
Identify the high-risk assumptions of the test plan. Specify contingency plans for each (for example,
delay in delivery of test items might require increased night shift scheduling to meet the delivery
date).

12.0 TOOLS
List the Automation tools you are going to use. List also the Bug tracking tool here. 
