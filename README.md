\# Selenium Automation Framework



\## Overview

This is a \*\*Maven-based Selenium Automation Framework\*\* using \*\*Java\*\* and \*\*TestNG\*\*.  

It is designed for web application testing with a clean \*\*Page Object Model (POM)\*\* structure, reusable utilities, and integration with Excel and ExtentReports for reporting.



---



\## Tech Stack

\- \*\*Java 17\*\*  

\- \*\*Selenium 4.21.0\*\*  

\- \*\*TestNG 7.9.0\*\*  

\- \*\*Apache POI 5.2.5\*\* (for Excel handling)  

\- \*\*ExtentReports 5.1.1\*\* (HTML test reports)  

\- \*\*WebDriverManager 5.8.0\*\* (automatic driver management)  

\- \*\*Maven\*\* (project \& dependency management)  

\- \*\*GitHub\*\* (version control)



---



\## Project Structure



SeleniumProject/

│

├─ src/main/java/com/automation/pages # Page classes

├─ src/main/java/com/automation/utilities # Reusable utilities

├─ src/test/java/tests # TestNG test classes

├─ pom.xml # Maven dependencies \& plugins

└─ .gitignore # Ignored files





---



\## How to Run Tests



\### 1. Clone the repository

```bash

git clone https://github.com/sanjay-64/OrangeHRM.git

cd OrangeHRM



mvn clean test



Features



Page Object Model (POM) implemented



Parallel execution support via TestNG testng.xml



Excel data handling using Apache POI



Configurable via BaseTest and utilities



Logging using Log4j2



Recommended IDE



Eclipse or VS Code (both free and support Java + Maven projects)



Notes



Keep chromedriver updated for latest Chrome version or use WebDriverManager.



Ensure Java 17 and Maven are installed and configured in system PATH.



You can run tests in parallel by configuring parallel="tests" and thread-count in testng.xml.









Author



Sanjay Kumar



