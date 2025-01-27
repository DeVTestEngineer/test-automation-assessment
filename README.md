# test-automation-assessment 

📋 Table of Contents 

1 - Project Overview
 
2 - Technology Stack

3 - Setup

4 - Runing Tests

5 - Test Data Configuration

6 - Reports 

7 - Project Structure  

8 - Framework Details

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
 
* Setup
1. Clone the repository:  
   `git clone https://github.com/yourusername/test-automation-assessment.git`
2. Navigate to the project directory:  
   `cd test-automation-assessment`

* Running Tests
1. **Run all tests**:  
  `mvn clean test`
2. **Run specific test group**:  
  Update `testng.xml` to include/exclude test classes.

* Test Data Configuration
1 - Edit `src/test/resources/config.properties` to modify URLs, search terms, or file paths.

* Reports
1 - Generated in `target/test-reports/ExtentReport.html`.
2 - Screenshots are attached for failed GUI tests.  
3 - API response bodies are logged in the report.

* Project Structure
1. **Page Objects**: `src/main/java/pages/`  
2. **Test Classes**: `src/test/java/tests/`  
3. **Configuration**: `src/test/resources/config.properties`  
4. **Test Data**: `src/test/resources/images/`  

* Framework Details
1. **Design Pattern**: Page Object Model (POM)  
2. **Reporting**: ExtentReports with screenshots and API response logging  
3. **External Data**: `config.properties` for URLs and dynamic values  
