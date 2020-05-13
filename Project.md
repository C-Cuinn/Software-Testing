# Software-Testing
Software Testing 

Prepared by: Ciaran Quinn G00361840
12/05/2020

Index

1.0 - **INTRODUCTION** <br>
2.0 - **OBJECTIVES AND TASKS** <br>
2.1 - **Objectives** <br>
2.2 - **Tasks** <br>
3.0 - **SCOPE** <br>
4.0 - **Testing Strategy** <br>
4.1 - **Unit Testing** <br>
4.2 - **System and Integration Testing** <br>
4.3 - **Performance and Stress Testing** <br>
4.4 - **User Acceptance Testing** <br>
4.5 - **Batch Testing** <br>
4.6 - **Automated Regression Testing** <br>
4.7 - **Beta Testing** <br>
5.0 - **Test Schedule** <br>
6.0 - **Control Procedures** <br>
7.0 - **Features to Be Tested** <br>
8.0 - **Features Not to Be Tested** <br>
9.0 - **Resources/Roles & Responsibilities** <br>
10.0 - **Schedules** <br>
11.0 - **Risks/Assumptions** <br>
12.0 – **Tools** <br>

 1.0 **INTRODUCTION** :<br>
  This document will describe and track the testing of the game "**Pixel Wizard**" as laid out in the brief distributed to us by the games 
  creator and developer for the 2020 Software testing project. It will document every aspect of the testing process in necessary depth.   <br>
  The Game being tested is a **2D** Castlevania-esque side scrolled with exploration elements in line with those of : The Elder Scrolls :    Skyrim, Salt and Sanctuary, Dark Souls.<br>
  The Main gameplay loop requires the player to advance through a selection of progressively harder levels defeated a boss at the end of  each. The levels will contain pickups to act as modifier to mix up the gameplay experience as well as health pickups etc.<br>
  Player traversal will be compatible with both mouse and keyboard as well as mobile devices. For keyboard and mouse the movement will be   controlled with AD with a jump assigned spacebar. On mobile there will be virtual representations of each of these keys.<br>
  Combat will be controlled with M1 or R on pc with mobile being controlled by a virtual representation of these keys.<br>
  On start up the player is greeted with the main menu which will have the core functions of the game such as "Play" ,"Load Game"(Within   which will be an additional option to load a specific save(Transitioning the player to the selected level) or delete a specific         save), Options where the player can modify the volume/gamma/etc ,and Quit to exit the application. <br>
  When the player selects the "Play" option it shall transition the player to the first level of the game. When in game the pause menu     will contain a "Save" option to save the players current location and status(Health etc) which can then be loaded from the main menu     along with a "Quit" button to return to the main menu. <br>
  
 2.0 **OBJECTIVES AND TASKS** :<br>
  The objective of this testing program is to ensure the game is of quality and meets all relevant standards in accordance to GSA   
  (**Gaming Standards Association**) protocols and other relevant standards :<br>
 
 A.G2S MESSAGE PROTOCOL V3.1 <br>
 B.S2S MESSAGE PROTOCOL V2.0 <br>
 C.GDS NOTE ACCEPTOR COMMUNICATIONS PROTOCOL V1.4 <br>
 D.PKG MANIFEST FILE FORMAT V1.1 <br>
 E.GSA POINT-TO-POINT WEBSOCKET TRANSPORT SPECIFICATION V2.0 <br>
 F.GDS PERIPHERAL MANIFEST FILE FORMAT V1.0 <br>
 G.PLAYER USER INTERFACE STANDARD V1.1 <br>
 H.GSAEGM MEDIA DISPLAY INTERFACE PROTOCOL V3.1 <br>
 I.SSI SIMPLE SYSTEM INTERFACE V1.1 <br>
 J.GSA THIRD PARTY GAME INTERFACE V1.0 <br>
 <br>
 The interpersonal communications will be handled by Microsoft teams .<br>
 Issue tracking, progress tracking and roles will be tracked on GitHub with a backup of this information publicly displayed on Trello.<br>
 2.1 **Objectives**:<br>
 The objectives of this testing phase will be to ensure adherence to the GSA standards and guidelines. It will focus on all testable
 aspects of the game such as design, performance, accessibility and user friendliness.
 The testing will primarily revolve around quality assurance and the pursuit of high quality thoroughly tested, and  fully functional end   product. 
 The Interfaces will be tested to assure that they conform to the standards layed out in the PUIS V1.1.
 The project will be divided up into tasks . Each task will be tackled by a dedicated team as to ensure focus on specific areas of     
 testing.
 
 2.2 **Tasks** :<br>
 Task 1 : Menu testing , usability , intuitive design.<br>
 Task 2 : Gameplay testing , Bug finding , Exploit detection.<br>
 Task 3 : Combat testing , pickup collection.<br>
 
 3.0 **Scope** :<br>
 vgbuhinjom
 
 4.0 **Testing Strategy**: <br>
 All Groups will have a specific assigned task which they will work on simultaneously while communicating with other task teams to share information on issues which may effect other aspects being tested by other teams.
 
 4.1 **Unit Testing** : <br>
Is a level of software testing where individual components of a program/project are tested. The purpose is to validate that each unit of the software performs as designed. Unit testing will be employed by all teams for all tasks as it the best  way to ensure the most issues are found.

 4.2 **System and Integration Testing**: <br>
Is defined as a type of software testing carried out in an integrated hardware and software environment to verify the behaviour of the complete system. It also verifies a software system's coexistence with others and tests the interface between modules of the software application.
 
 4.3 **Performance and Stress Testing** : <br>
Stress testing is a form of deliberately intense or thorough testing used to determine the stability of a given system. It involves testing beyond normal operational capacity, often to a breaking point, in order to observe the results.
 
 4.4 **User Acceptance Testing** : <br>
Acceptance testing is also known as user acceptance testing (UAT), end-user testing, operational acceptance testing (OAT), acceptance-test-driven development (ATTD) or field (acceptance) testing. Acceptance criteria are the criteria that a system or component must satisfy in order to be accepted by a user.
 
 4.5 **Batch Testing** : <br>
Batch testing is performed by running the entire test set. All automated test scripts are executed one at a time by keeping the other scripts in waiting mode. 
 
 4.6 **Automated Regression Testing** : <br>
 Regression testing is re-running functional and non-functional tests to ensure that previously developed and tested software still performs after a change.
 
 4.7 **Beta Testing** : <br>
A field test of the beta version of a product (such as software) especially by testers outside the company developing it that is conducted prior to commercial release
 
 5.0 **Hardware Requirements** : <br>
 The hardware requirements for this will be based off my experience with similar games and the games listed in the brief of which I have
 had previous experience through either playing them myself or by in depth research conducted in pursuit of this information.
  ________________________________________________________________

 **Minimum Specifications** : <br><br>
 OS : Windows : XP/Vista/7/8/10 ,Temple OS <br>
 Graphics : GTX 970 <br> 
 CPU : 2.2GHz Dual Core <br>
 Memory : 4GB RAM <br>
 Storage : 50GB free space<br><br>
 
 **Recommended Specifications** :<br><br>
 OS : Windows 10, Temple OS <br>
 Graphics : GTX 3080 TI super <br>
 CPU : 5.3GHz 10core 20t <br>
 Storage : 500GB free space<br>
 
 ________________________________________________________________

 
 6.0 **Environment Requirements** : <br>
 
 6.1 **Main Frame** : <br>
 
 6.2 **Workstation** : <br>
 
 7.0 **Test Schedule** : <br>
 
 8.0 **Control Procedures** : <br>
 
 9.0 **Features to Be Tested** : <br>
 **GUI** : <br>
     All buttons should be tested to ensure that they do what they are supposed to 99.999% of the time.<br>
     All sliders (Volume ,Gamma ,etc) should modify the relevant values in a proportional and intuitive way.<br>
     Menus should load quickly with little to no slowdown or latency.<br>
     Menus should be responsive and clearly labelled.<br>
     Menu traversal/navigation.<br>
     Secondary menus (Pause menus, Options menus).<br>
     
 **Gameplay** : <br>
     The map and relevant areas should be tested for exploits such as "Out-of-bounds" glitches.<br>
     Loading zones/transition zones should trigger when interacted with in an intuitive way.<br>
     Combat.<br>
     Player movement and traversal.<br>
     Difficulty scaling.<br>
     
 
 10.0 **Features Not to Be Tested **: <br>
 All aspects of this game should be tested as all aspects are integral to the players experience with the product.
 
 11.0 **Resources/Roles & Responsibilities** : <br>
 
 12.0 **Schedules**: <br>
 
 13.0 **Significantly Impacted Departments** : <br>
 
 14.0 **Dependencies** : <br>
 
 15.0 **Risks/Assumptions** : <br>
 There are several risks to be considered at the outset of this project ."deadline"
 
 16.0 **Tools** : <br>
 The main tools to be used for this testing project are :<br>
 
**Ranorex** :<br> An all-in-one tool for test automation. Ranorex is easy for beginners with a codeless click-and-go interface, but powerful for automation experts with a full IDE for C# or VB.NET, and open APIs. Functional UI and end-to-end testing on desktop, web, and mobile.
Cross-browser testing. SAP, ERP, Delphi and legacy applications. Run tests locally or remotely, in parallel or distribute on a Selenium Grid. Robust reporting. Ranorex integrates with leading solutions like Git, TFS, Jenkins, Bamboo, Bugzilla, SpecFlow, NeoLoad, TestRail and more for a complete testing toolchain.<br>

**TestCraft** :<br> A codeless Selenium test automation platform. The revolutionary AI technology and unique visual modelling allows for faster test creation and execution while eliminating test maintenance overhead. Testers create fully automated test scenarios without coding. Customers find bugs faster, release more frequently, integrate with CI/CD and improve overall quality of their digital products.
No programming skills required. Leverage manual testers’ business knowledge and allow them to create automated test scenarios
Substantially reduce maintenance costs. Scripts are automatically adjusted to change due to our AI mechanism.
Selenium based. Quickly integrate and leverage modules developed by the community
Provides immediate time to value. Easy to master.<br>

**Bugzilla** : <br>A leading Bug Tracking tool widely used by many organizations for quite some time now. It is very simple to use, web-based interface. It is completely open sourced and is free to use.<br>
 
 17.0 **Approvals** : <br>
