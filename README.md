# 📚 Book Library API Tests

Portfolio project with REST API Automated tests for a fictional Book Library service.
The project demonstrates QA automation proficiency in using best practices of automated API tests development using
Python, Pytest, Requests, Allure, GitHub Actions CI and data-driven tests which cover real-world contract API and e2e scenarios.

## 🧰 Tech Stack

- **Language:** Python 3.11
- **Framework:** Pytest
- **Libraries:** requests, Faker, Allure, Pydantic
- **CI/CD:** GitHub Actions
- **Reports:** Allure HTML reports

## Key Features

- **Full CRUD E2E API coverage** (create, read, update, delete books)
- **Contract validation** with Pydantic schemas
- **Advanced test data management** (tracked resource creation and cleanup)
- **Allure reporting**: steps, attachments, environment info, trends
- **GitHub Actions CI/CD**: automatic runs and Allure artifacts
- **Clean code, Pytest best practices**

## Project Structure

- **data/** # payload generators
- **utils/** # API client, resource tracker, cleanup scripts
- **schemas/** # Pydantic models for response validation
- **tests/** # All test cases divided by suites
- **config/** # env, other configs
- **reports/** # Allure results and report artifacts
- **run_tests_with_trend.sh** # universal launcher script

## Author

Vera Paikina — Senior QA Engineer / QA Automation 
