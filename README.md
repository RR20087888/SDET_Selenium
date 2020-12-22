# SDET_Selenium
For all the below Assignment below are the activities to be done:						
1.    Prepare test cases (positive and negative) covering all test data combination. Test case excel should be named on your respective name and below is the format:						
Test Case Id	Test case Name	Pre-Requiste	Test Description	Test Steps	Test Data	Expected
						
						
2. Create a Maven Project with Selenium TestNG Framework,Page object Model, add logs and create Extent Report						
3.    Write Selenium scripts and automate all the test cases for all the assignments for 2 browser – Chrome and Firefox. Create the test scripts prefixed with your name.						
4.    Commit the code in github. Register your wipro email id in github and share the url						
						
7. Standards to follow : 						
* There should be validations step for all the actions done. Without validation automation script is not called valid script.						
* There should not be any hardcoded data inside the script						
*  Test Data should be managed by @Dataprovider annotation for TestNG, JSON file, Excel, CSV file or From database. All these should be used atlest once. 						
*  data.properties file should be used only for configuration purpose not for test data 						
*  Try to avoid Thread.sleep() method instead use Implicit and Explicit wait concept.						
*  Write comments while writing script it will help to understand what the script is doing						
*  Make use of Java Oops cancepts, collectons etc… in your script						
						
Assignment 1:						
Automate the below mentioned site						
1)    http://www.demoqa.com/selectable						
						
2)    http://www.demoqa.com/automation-practice-form						
						
3)     http://www.demoqa.com/droppable						
please select the Drag me to my target and drop on the target and verify the text.						
						
4)      http://www.demoqa.com/date-picker						
Please select your Date of Birth in a Calendar. Use a logic of date picker, don’t send it from sendkeys directly						
						
5)      http://www.demoqa.com/select-menu						
Please select the All the menu options one by one.						
						
Assignment 2:						
Automate the below mentioned site for Registration and Login						
1)    Olay website user registration and sign in						
2)    Validate invalid password validation, forgot password						
Register a user id and sign in for 3 different language 						
a)     UK English - https://www.olay.co.uk/en-gb						
c)     Germany  - https://www.olaz.de/de-de						
d)    Spain - https://www.olay.es/es-es						
Special Instruction : Same Login, Registration, invalid password, forgot password script should work for all the countries. Backend code will be same for development, there may be change in the fields. That should be handled by logic						
						
Assignment 3:						
Automate the below mentioned site for booking and reviewing it						
1)      https://www.makemytrip.com/						
Step 1:Launch Make my trip website ( makemytrip.com)						
Step 2: Select any one option( Oneway ,Roundtrip,Multi City)						
Step 3: Select From & To						
Step 4: Select the Departure date in future						
Step 5: Search for the cheapest price and click on Book now button						
Step 6: Review the selection in the review page (please note need not submit booking						
						
