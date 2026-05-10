# Selenium Java Framework Starter

Reusable Selenium Java Automation Framework using TestNG, Maven, Page Object Model, Data-Driven Testing, Extent Reports, and Config Management.

---

## Features

- Selenium WebDriver
- Java + Maven
- TestNG Framework
- Page Object Model (POM)
- Data-Driven Testing using Excel
- Config File Support
- Extent Report Integration
- Reusable Utility Classes
- TestNG XML Execution
- Screenshot Capture Utility
- Scalable Framework Structure

---

## Project Structure

src/test/java
│
├── base
├── pages
├── tests
├── utilities
├── listeners
├── testdataManagement
│
src/test/resources
│
├── configfiles
├── testdata

---

## Technologies Used

- Java
- Selenium WebDriver
- TestNG
- Maven
- Apache POI
- Extent Reports

---

## Setup Instructions

### Clone Repository

git clone <your-github-url>

### Install Dependencies

mvn clean install

### Run Test Suite

Right click on:
testng.xml

OR run using Maven:

mvn test

---

## Reporting

Extent Report generated at:

test-output/AutomationReport.html

---

## Framework Components

### ConfigReader
Handles environment-based configuration management.

### ExcelUtils
Reads test data from Excel files using Apache POI.

### DataProvider
Supports data-driven testing.

### Extent Reports
Generates detailed HTML execution reports.

### Screenshot Utility
Captures screenshots automatically on failures.

---

## Future Enhancements

- Jenkins CI/CD Integration
- Cross Browser Execution
- Parallel Execution
- Docker Support
- GitHub Actions Integration

---

## Author

Sumit Nanda
Senior QA Automation Engineer
