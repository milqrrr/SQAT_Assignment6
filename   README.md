# Assignment 6 – Automated Testing with Selenium, DDT, and BrowserStack

## Project Description

This project was created as part of **Assignment 6** for the Software Quality Assurance and Testing course.  
The goal of the assignment is to implement automated functional testing using Selenium WebDriver with a Data-Driven Testing (DDT) approach and demonstrate cloud-based cross-browser execution using BrowserStack.

The system under test is the ParaBank demo banking application:

https://parabank.parasoft.com/parabank/index.htm

---

## Assignment Objectives

The main objectives of this project are:

- Create automated Selenium tests using Python  
- Implement Data-Driven Testing using Excel  
- Execute tests locally on a real browser  
- Execute tests in the cloud on multiple browsers  
- Use pytest as the testing framework  
- Generate test execution reports  
- Collect evidence of successful cloud execution  

---

## Technologies and Tools Used

- **Python** – programming language  
- **Selenium WebDriver** – browser automation  
- **pytest** – test framework  
- **openpyxl** – reading Excel test data  
- **BrowserStack Automate** – cloud testing platform  
- **pytest-html** – test reporting  
- **Google Chrome** – local browser  
- **Mozilla Firefox** – cloud browser  

---

## Project Structure

SQAT_6/
│
├── data/
│ └── testdata_parabank_login.xlsx # Excel file with test cases
│
├── tests/
│ ├── test_ddt_parabank_login.py # Local DDT tests
│ └── test_browserstack_parabank.py # Cloud cross-browser tests
│
├── report.html # Generated HTML test report
├── README.md # This documentation file
└── requirements.txt # Project dependencies

---

## Test Data

All test cases are stored in an external Excel file:


### Excel Columns

- `test_id` – unique identifier  
- `url` – application URL  
- `username` – login username  
- `password` – login password  
- `expected` – expected result (success or error)

This approach allows easy modification and extension of test cases without changing the code.

---

## Prerequisites

To run this project, you need:

- Python 3.x installed  
- Google Chrome installed  
- Git (optional, for version control)  
- Internet connection  
- BrowserStack account (for cloud testing)

---

## Installation

### 1. Clone the Repository

