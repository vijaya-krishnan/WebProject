# WebProject
Created new repository for the webproject using playwright

# Project Name : Web Automation: Flight Booking

# Project Scope:
Frame work : Hybrid + POM pattern + utilties+ Listeners + TestNG + Extent Reports

#Libraries and Version:
1. playWright - 1.25.0 
2. IDE - IntelliJ IDEA 2022.3.1
2. TestNG - 6.14.3
3. Maven compiler - 3.8.1
4. ExtentReportListener 

# project setup guide lines:
1. Import the project in any IDE
2. Perform the maven update project
3. Execute the Playwright-webproject-master --> src --> test -->resources -->  testrunners --> testng_WebProjectTestSuite.xml
4.  Right click on "testng_WebProjectTestSuite.xml" run it
5. Once Execution is done. Results will able available on project folder path : Playwright-webproject-master\build
file:///C:/User/Playwright-WebProject/Playwright-WebProject-master/build/TestExecutionReport.html#


#project Approach:
I have created the hybrid framework (POM+ TestNG +Utilities + Libraries + Data driven+ Extent reports) Which following the page chaining approach along with base test class defined separately. I have kept the playwright factory class for all the browser initializations’ and kept base test for before method and after method execution on the testcases. I have ingested the extent report listeners class which gives more concrete execution reports which I like it most. 

#Estimation Time for completion : 1.5 Days

#Chanllenges faced:
1. More dynamic and frames in the complex webpage which is deficult for write unique locator for it.
2. More often received the webpage Err_ cache miss issue which is inconsistently happening to  handle in script level.

# Estimation time for the project : 12 Hours

#Pending items: As mentioned in the assignment task is completed however Page chaining model should be extended across all the pages in web site.
