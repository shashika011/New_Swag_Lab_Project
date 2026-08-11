# Swag Labs Automation Testing Project

## 📌 Project Overview

This project is an end-to-end web automation testing framework developed using **Selenium WebDriver, Java, TestNG, and Maven**.

The project automates functional test scenarios for the **Swag Labs** web application and demonstrates practical implementation of UI automation, test data management, reporting, logging, and CI/CD execution.

The framework is designed with maintainability and reusability in mind and can be extended with additional test scenarios and automation utilities.

## 🛠️ Technologies & Tools

| Technology / Tool | Purpose |
|---|---|
| Java | Programming language |
| Selenium WebDriver | Web UI automation |
| TestNG | Test execution and assertions |
| Maven | Build and dependency management |
| WebDriverManager | Browser driver management |
| Apache POI | Excel test data handling |
| ExtentReports | Test reporting |
| Allure Reports | Test execution reporting |
| Log4j | Application/test logging |
| JavaFaker | Test data generation |
| Git / GitHub | Version control |
| GitHub Actions | CI/CD automation |

## 📦 Maven Dependencies

The project uses the following key dependencies:

- Selenium 4.24.0
- TestNG 7.10.1
- WebDriverManager 5.9.2
- Apache POI 5.4.0
- ExtentReports 5.0.9
- Allure TestNG 2.30.0
- Log4j 2.23.1

## 🏗️ Project Structure

```text
NewSwagLab_Project
│
├── .github
│   └── workflows
│
├── Drivers
├── Reports
├── Screenshots
├── TestData
├── XMLFiles
├── logs
│
├── src
│   └── test
│       └── java
│
├── target
├── test-output
│
├── pom.xml
├── .gitignore
├── LICENSE
└── README.md
🧪 Testing Scope

The automation framework covers functional testing scenarios such as:

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
🔧 Framework Features
Selenium WebDriver automation
Java
TestNG
Maven
Page Object Model concepts
WebDriverManager
Explicit waits
TestNG assertions
TestNG XML suites
Excel test data handling
Screenshot capture
Extent Reports
Allure Reports
Log4j logging
Git/GitHub
GitHub Actions
🚀 How to Run
Clone the Repository
git clone https://github.com/shashika011/NewSwagLab_Project.git
Navigate to the Project
cd NewSwagLab_Project
Install Dependencies
mvn clean install
Run Tests
mvn test
📊 Test Reports

The project supports:

TestNG Reports
Extent Reports
Allure Reports

Allure report can be generated using:

allure generate target/allure-results --clean -o allure-report

Then open the report:

allure open allure-report
🔄 CI/CD

The project includes a GitHub Actions workflow for executing automated tests as part of a CI/CD pipeline.

Workflow files are maintained under:

.github/workflows/
🎯 Skills Demonstrated
Selenium WebDriver
Java
TestNG
Maven
WebDriverManager
UI Automation
Functional Testing
Data-Driven Testing
Excel Test Data
Test Reporting
Logging
Git & GitHub
CI/CD
👨‍💻 Author

Shashika Thilan

QA Team Lead / Senior QA Engineer
