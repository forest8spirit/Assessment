# Assessment
CIB DIGITAL TECH – QA AUTOMATION ASSESSMENT


Download Assessment.zip from https://github.com/forest8spirit/Assessment/blob/master/QA%20Automation%20Assessment.zip
Extract Assessment.zip to C:\

Task 2 - WEB:
---

Open latest version of Google Chrome browser 

Browse to https://chrome.google.com/webstore/detail/katalon-recorder-selenium/ljdobmomdgdljniojadhoplhkpialdid

Click 'Add to Chrome' > 'Add extension'

Click the Katalon Recorder extension icon in toolbar to open


Click  Open Test Suite > C:\QA Automation Assessment\Web test - Katalon Recorder

Select Task 2 -Web.html

Click Open
       
Task 2 -WEB (Test Suite)       
- WebTest_Open_WebTables
- WebTest_Populate_Data
- WebTest_Verify_Data


Click on the 'Data Driven' tab 

Click Add CSV File > C:\QA Automation Assessment\Web test - Katalon Recorder

Select data.csv

Click Open


Click 'Play Suite' to execute test


Click Log tab to view log

Click Screenshots to view screenshots

Click 'Save log as...' to save log vile in HTML format


Task 1 - API:
---
Install Katalon Studio from https://www.katalon.com/download/ (301MB). No need to register.

Extract the Katalon_Studio_Windows_64-5.7.0.zip archive and run the katalon.exe


Click File > Open Project > C:\QA Automation Assessment\API test - Katalon Studio\Task 1 -API


Navigate to Test Cases > Task 1 - API to verify individual Test Cases 

- Task1_API_01_list_of_all_dog_breeds
- Task1_API_02_verify_retriever_breed_is_within_the_list
- Task1_API_03_sub-breeds_for_retriever
- Task1_API_04_List_random_link_for_the_sub-breed_golden

Double Click on Test Cases to open

Select Manual Tab to view Keyword view

Select Script tab for code view

Click Run to execute test case 
  
Test results writen to Log Viewer and Console view


For test Task1_API_02_verify_retriever_breed_is_within_the_list the result is writen to 
file: C:\QA Automation Assessment\API test - Katalon Studio\Verify_Retriever_in_List.txt

- Result contains retriever is true (present)
- Result contains retriever is false (not present)
        
Object Repository folder contains Web Service Request used by Test Cases        

Double click  on WS Request and click run to view response 



Test Suites folder contains Assessment test suite

Double click 'Assessment' for Execution Information

Click run to execute all selected test in the suite

Results available in Log Viewer and Console view.

Reports folder contains reports generated through test suite execution



Open Reports > Assessment > double click latest report to view results

Right click on report > Export as > <select option> to view report



