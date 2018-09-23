# SerenityAutomationWithBDD
Automated web tests using Serenity and Maven
The Repository contains zip file which includes
1. pom.xml
2. src->test->java->com->org->contains all 4 java files 
3. Target contains->generated classes,serenity HTML reports

## Part A
1. Retail Web Application Automation

### File Location
  src->test->java->com->org
- Test File->RetailAutomationTestUser.java  
  > This file contains all the test scenarios.
- Step File->SeleniumAutomation.java 
  > All the Logical implementation for the test scenarios is implemented in SeleniumAutomation file.

In Serenity BDD we will run the Test Java File 

* Web Application is automated using Selenium Webdriver tool with JAVA in Serenity BDD Framework
* I choose serenity because it follows a BDD so the requirement can be clearly defined by any stake holder 
* Serenity also aids in generated test results in a HTML format,So that everyone can have a clear idea of requirement,Passes,Failed test cases and each of its duration
* To run Retail Web Application test run the below commands in CMD <br/>
    > **mvn verify** <br/>
    > **mvn -Dtest=RetailAutomationTestUser test**
*  To view the result navigate to Target->Site->Serenity->index.html in project folder will show the test result in HTML format
*  I choose Chrome as Webdriver 


##  Part B
1. API Automation

### File Location
src->test->java->com->org
- Test File->CurrencyConversionUser.java 
  > This file contains all the test scenarios.
- Step File->APIAutomation.java 
  > All the Logical implementation for the test scenarios is implemented in APIAutomation file.

In Serenity BDD we will run the Test Java File 

* API is automated using REST Assured with JAVA in Serenity BDD Framework
* I choose serenity because it follows a BDD so the requirement can be clearly defined by any stake holder 
* Serenity also aids in generated test results in a HTML format,So that everyone can have a clear idea of requirement,Passes,Failed test cases and each of its duration
* To run Retail Web Application test run the below commands in CMD <br/>
    > **mvn verify** <br/>
    > **mvn -Dtest=CurrencyConversionUser test**
* To view the HTML result navigate to Target->Site->Serenity->index.html in project folder 
* I choose POSTMAN as tool ,Hence I was unable to use the get Data property mentioned in document


Sample serenity report screenshot is attached as PDF.
 
