# test-automation-assessment 

📋 Table of Contents 

1 - Project Overview
 
2 - Technology Stack

3 - Project Structure

4 - Key Components

5 - Setup & Execution

6 - Reports & Artifacts

7 - Bonus Points Achieved

-------------------------------------------------------------------------------------------------------------------------------------
🚀 Project Overview 

This framework automates Web GUI and API test scenarios outlined in the assessment. It uses:

* Selenium WebDriver for browser automation.

* RestAssured for API testing.

* Page Object Model (POM) for maintainable UI interactions.

* ExtentReports for detailed test execution reporting.

* Maven for dependency management and build automation.
-------------------------------------------------------------------------------------------------------------------------------------- 
 
🛠 Technology Stack

| Component               | Technology/Framework       |
|-------------------------|----------------------------|
| Programming Language    | Java 11                    |
| Build Tool              | Maven 3.8+                 |
| Web Automation          | Selenium WebDriver 4.10.0  |
| API Testing             | RestAssured 5.3.0          |
| Reporting               | ExtentReports 5.1.0        |
| Test Framework          | TestNG 7.8.0               |
| Browser Driver Management | WebDriverManager 5.3.3   | 
------------------------------------------------------------------------------------------------------------------------------------------  
Project structure 

test-automation-assessment/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── pages/
│   │   │   │   ├── GoogleSearchPage.java
│   │   │   │   ├── HerokuAppMainPage.java
│   │   │   │   ├── FileUploadPage.java
│   │   │   │   ├── DynamicLoadingPage.java
│   │   │   ├── utilities/
│   │   │   │   ├── BaseTest.java
│   │   │   │   ├── ConfigReader.java
│   │   │   │   ├── ReportManager.java
│   │   ├── resources/
│   ├── test/
│   │   ├── java/
│   │   │   ├── tests/
│   │   │   │   ├── GoogleSearchTest.java
│   │   │   │   ├── FileUploadTest.java
│   │   │   │   ├── DynamicLoadingTest.java
│   │   │   │   ├── CatFactsAPITest.java
│   │   ├── resources/
│   │   │   ├── config.properties
│   │   │   ├── images/
│   │   │   │   ├── test-image.jpg
├── target/
│   ├── test-reports/
│   │   ├── ExtentReport.html
│   │   ├── screenshots/
├── pom.xml
├── README.md
