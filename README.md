# **API Assignment - DMoney API Testing with Newman**

## **Content**
1. [Introduction](#introduction)
2. [Test Cases Scenario](#test-cases-scenario)
3. [API Endpoint Details](#api-endpoint-details)
4. [How to run the project](#how-to-run-the-project)
5. [Postman API Documentation Link](#postman-api-documentation-link)
6. [Technology Used](#technology-used)
7. [Project Structure](#project-structure)
8. [Newman Report](#newman-report)

## Introduction

This project is a Postman/Newman automated test suite for a Mobile Financial Service (MFS) REST API, simulating financial transactions where users transfer virtual/demo money between Admin, Agent, Customer, and Merchant accounts.

## Test cases scenario

1. Admin Login.
2. Admin creates a 2 Customer, 1 Agent, 1 Merchant.
3. System logs in and deposits money to the Agent.
4. Agent logs in and deposits money to Customer 01.
5. Customer 01 logs in and sends money to Customer 02.
6. Customer 02 logs in, cashes out to Agent, and pays a Merchant bill.

## API Endpoint Details

- **User API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/user_](https://dmoney.roadtocareer.net/api-docs/user)

- **Transaction API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/transaction_](https://dmoney.roadtocareer.net/api-docs/transaction)
- **Partner Key**: X-AUTH-SECRET-KEY: `ROADTOSDET`

## How to run the project

- Clone this project
   ```console
   git clone https://github.com/rashadkhan97/dMoney_Postman-API-with-Newman_B19.git
   ```
- Open with any code editor / Command Shell
- Give the following command ```npm i``` and ```node .\report.js```

## Postman API Documentation Link
  
  - API Documentation Link: Not able to publish yet as postman issue

## Technology Used
- Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
- Newman
- newman-reporter-htmlextra

## Project Structure

```
API-Assignment/
├── Collection/
│   └── Dmoney_Assignment.postman_collection.json   # Postman collection
├── Reports/
│   └── report.html                                  # Generated Newman HTML report
├── report.js                                         # Newman runner script
└── package.json
```

## Newman Report
<img width="613" height="601" alt="image" src="https://github.com/user-attachments/assets/54666360-e53c-417a-aa1d-7ece37492ced" />

