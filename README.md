#TestAutomation
================================


READ ME file for framework

Prerequisites:
=============
1. Properties file - 
2. Extent Report - To generate user friendly report
3. Jenkins - integration to framework.
4. GIT - to store the code
5. Apache POI - excel interaction[ read/write]
6. TestNg - annotations, testng.xml file
7. Maven - as dependency tool

Test Scenario implemented:
========================
1. Launch weathershopper  site 
2. click on sunscreen category
3. Add an item to the cart
4. Click on Paynow button
5. Enter all the payment details
6. Place the order

Browser EXE files versions used :
================================
ChromeBrowser = 97.0.4692.71
FirfoxBrowser = 95.0.2



Page Object Model (Framework):
====================
It is a framework in which we write all the functionalities of a page that we want to automate in a separate class.The main advantage of using this framework is that it becomes 
easy for a automation tester to identify the place to change the script as per the requirement/UI changes for any page.
- Reduces the maintenance effort
- It allows to reuse the components
- It easy to add, modify or debug the test cases while executing.

TestNg
==========
Advantages of using Testng is that:-
a). It allows parallel execution
b). Annotations
c). Report generation
d). We can create dependency and also set the priority.

Maven:
=====
It downloads all the dependencies,if we define all the artifacts in pom.xml.
Individual  downloads are not required here.

GITHuB
======
This is used to store all the code changes in a repository.
If many people are working on automation team, it helps in committing the code changes, updates and deletion without any complications.

Jenkins
=======
It is a continous integration tool where testers can run the build and can generate the report.
    
