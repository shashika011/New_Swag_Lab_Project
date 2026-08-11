📌 Project Overview

This project is an end-to-end web automation testing framework developed using Selenium WebDriver, Java, TestNG, and Maven.
The project automates functional test scenarios for the Swag Labs web application and demonstrates practical implementation of UI automation, test data management, reporting, logging, and CI/CD execution.
The framework is designed with maintainability and reusability in mind and can be extended with additional test scenarios and automation utilities.

🛠️ Technologies & Tools
Technology / Tool	Purpose
Java	Programming language
Selenium WebDriver	Web UI automation
TestNG	Test execution and assertions
Maven	Build and dependency management
WebDriverManager	Browser driver management
Apache POI	Excel test data handling
ExtentReports	Test reporting
Allure Reports	Test execution reporting
Log4j	Application/test logging
JavaFaker	Test data generation
Git / GitHub	Version control
GitHub Actions	CI/CD automation

The current Maven configuration includes Selenium 4.24.0, TestNG 7.10.1, WebDriverManager 5.9.2, Apache POI 5.4.0, ExtentReports 5.0.9, Allure TestNG 2.30.0, and Log4j 2.23.1.

🏗️ Project Structure
NewSwagLab_Project
│
├── .github
│   └── workflows
│       └── GitHub Actions workflow
│
├── Drivers
│
├── Reports
│
├── Screenshots
│
├── TestData
│
├── XMLFiles
│   └── TestNG XML files
│
├── logs
│
├── src
│   └── test
│       └── java
│           └── Automation test classes
│
├── target
│
├── test-output
│
├── pom.xml
├── .gitignore
├── LICENSE
└── README.md

The repository currently includes Drivers, Reports, Screenshots, TestData, XMLFiles, logs, src/test, target, and test-output, together with the Maven configuration and GitHub Actions workflow.

🧪 Testing Scope

The framework can be used to automate functional scenarios such as:

User login
Product selection
Product sorting
Add product to cart
Remove product from cart
Cart validation
Checkout functionality
Form validation
Order completion
Negative test scenarios
🔧 Framework Capabilities
Selenium WebDriver

Used to automate browser-based interactions and validate the Swag Labs web application.

TestNG

TestNG is used for:

Test execution
Assertions
Test grouping
Test suites
Test annotations
Test configuration

Test suites can be configured using XML files located under the XMLFiles directory.

Maven

Maven is used to:

Manage project dependencies
Build the project
Execute automated tests
Integrate test reporting

Run the test suite using:

mvn clean test
📊 Test Reports

The project includes support for multiple reporting mechanisms:

Extent Reports

ExtentReports is used to generate detailed HTML-based test execution reports.

Allure Reports

Allure TestNG integration is configured in the Maven project.

After test execution, Allure results can be generated and viewed using the Allure command-line tools.

Example:

allure generate target/allure-results --clean -o allure-report

Then:

allure open allure-report
📸 Screenshots

Screenshots can be captured during test execution, particularly when a test fails.

The generated screenshots are maintained in the:

Screenshots/

directory.

📝 Test Data

Test data is maintained separately from the test implementation.

The project contains a:

TestData/

directory and Apache POI dependencies are configured in pom.xml for Excel-based test data handling.

🪵 Logging

Log4j is configured as part of the project to support test execution logging.

Logs are maintained under:

logs/

Logging helps with:

Debugging
Test execution tracking
Failure investigation
Troubleshooting automation issues
🔄 CI/CD

The project includes a GitHub Actions workflow under:

.github/workflows/

This allows the automation tests to be integrated into a CI/CD pipeline and executed automatically when configured in GitHub Actions.

🚀 Getting Started
Prerequisites

Install the following before running the project:

Java JDK
Maven
Git
Chrome / Firefox / Edge
Allure CLI if Allure reports are required
Clone the Repository
git clone https://github.com/shashika011/NewSwagLab_Project.git
Navigate to the Project
cd NewSwagLab_Project
Install Dependencies
mvn clean install
Run Tests
mvn test
▶️ Running a TestNG Suite

TestNG XML files are maintained in:

XMLFiles/

A suite can be executed from Eclipse using:

Right Click → Run As → TestNG Suite

or through Maven when the appropriate TestNG suite configuration is enabled.

📋 Example Test Flow
Launch Browser
      ↓
Open Swag Labs
      ↓
Login
      ↓
Validate Login
      ↓
Select Product
      ↓
Add Product to Cart
      ↓
Validate Cart
      ↓
Checkout
      ↓
Validate Order
      ↓
Generate Test Report
      ↓
Close Browser
🎯 Key Skills Demonstrated

This project demonstrates practical experience with:

Selenium WebDriver
Java
TestNG
Maven
WebDriverManager
Page Object Model concepts
Test automation
Functional testing
Data-driven testing
Excel test data
Assertions
TestNG XML suites
Screenshot capture
Logging
Extent Reports
Allure Reports
Git and GitHub
CI/CD with GitHub Actions
📈 Future Improvements

The framework can be further enhanced by adding:

Page Object Model improvements
Centralized WebDriver management
Configuration management
Parallel execution
Cross-browser execution
Data-driven framework
Retry mechanism
Custom TestNG listeners
Improved failure screenshots
Docker-based execution
Selenium Grid
Enhanced GitHub Actions pipeline
👨‍💻 Author

Shashika Thilan

QA Team Lead / Senior QA Engineer
