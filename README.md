# SerenityAutomationWithBDD
Automated web tests using Serenity and Maven
The Repository contains zip file which includes
1)pom.xml
2)src->test->java->com->org->contains all 4 java files 
3)Target contains->generated classes,serenity HTML reports

Part A
1)Retail Web Application Automation
File Location
src->test->java->com->org
1)Test File->RetailAutomationTestUser.java
2)Step File->SeleniumAutomation.java
Test contains the users actual test calling methods
Step contains the functional implementation
In Serenity BDD we will run the Test Java File 

*Web Application is automated using Selenium Webdriver tool with JAVA in Serenity BDD Framework
*I choose serenity because it follows a BDD so the requirement can be clearly defined by any stake holder 
*Serenity also aids in generated test results in a HTML format,So that everyone can have a clear idea of requirement,Passes,Failed test cases and each of its duration
*To run Retail Web Application test follow below step
mvn verify
mvn -Dtest =RetailAutomationTestUser test from cmd prompt
* To view the result navigate to Target->Site->Serenity->index.html in project folder will show the test result in HTML format
* I choose Chrome as Webdriver 


Part B
1)API Automation
File Location
src->test->java->com->org
1)Test File->CurrencyConversionUser.java
2)Step File->APIAutomation.java
Test contains the users actual test calling methods
Step contains the functional implementation
In Serenity BDD we will run the Test Java File 

*API is automated using REST Assured with JAVA in Serenity BDD Framework
*I choose serenity because it follows a BDD so the requirement can be clearly defined by any stake holder 
*Serenity also aids in generated test results in a HTML format,So that everyone can have a clear idea of requirement,Passes,Failed test cases and each of its duration
*To run Retail Web Application test follow below step
mvn verify
mvn -Dtest =CurrencyConversionUser test from cmd prompt
* To view the HTML result navigate to Target->Site->Serenity->index.html in project folder 
* I choose POSTMAN as tool ,Hence I was unable to use the get Data property mentioned in document


I have attached the sample serenity report screenshot
