# Test Plan - Swag Labs (SauceDemo)

## 1. Introduction

This document defines the testing approach for the Swag Labs e-commerce web application.

The objective is to validate the main business functionalities of the application and ensure that critical user journeys work as expected.


## 2. Test Objectives

The main objectives of testing are to:

- Verify that the main functionalities work as expected.
- Validate positive and negative user scenarios.
- Identify and document functional defects.
- Verify application behavior across supported browsers.
- Perform regression testing on critical functionalities.
- Validate critical end-to-end user journeys.
- Prepare selected test cases for automation.


## 3. Scope

### In Scope

The following modules will be tested:

- Authentication
- Product inventory
- Product details
- Product sorting
- Shopping cart
- Checkout
- Order confirmation
- Logout

### Out of Scope

The following areas are not included in the initial testing scope:

- Real payment processing
- Database testing
- Server-side testing
- Production environment testing
- Third-party integrations


## 4. Test Types

The following types of testing will be performed:

- Functional Testing
- Positive Testing
- Negative Testing
- Regression Testing
- Exploratory Testing
- UI Testing
- End-to-End Testing

Selected scenarios will later be automated using Playwright.


## 5. Test Environment

Application: Swag Labs - SauceDemo

Environment: Demo / Test

Browsers:

- Google Chrome
- Mozilla Firefox

Operating System:

- Windows

Test URL:

https://www.saucedemo.com/


## 6. Test Data

SauceDemo provides dedicated test accounts.

The following accounts may be used during testing:

- standard_user
- locked_out_user
- problem_user
- performance_glitch_user
- error_user
- visual_user

Password:

secret_sauce

Additional invalid and empty credentials will be used for negative testing.


## 7. Entry Criteria

Testing can begin when:

- The application is accessible.
- Test credentials are available.
- Functional requirements have been identified.
- The test environment is available.


## 8. Exit Criteria

Testing can be considered complete when:

- All planned critical test cases have been executed.
- Critical user journeys have been validated.
- Identified defects have been documented.
- No unresolved blocker defect prevents completion of critical flows.
- A test summary report has been prepared.


## 9. Test Deliverables

The project will produce:

- Functional Requirements
- Test Plan
- Test Cases
- Test Execution Results
- Bug Reports
- Exploratory Testing Notes
- Test Evidence
- Test Summary Report
- Automated Test Scripts


## 10. Tools

The following tools will be used during the project:

- GitHub - Test documentation and version control
- Google Chrome / Mozilla Firefox - Manual testing
- Playwright - Web test automation
- Python / Pytest - Automated test execution


## 11. Risks

Potential testing risks include:

- Demo environment instability
- Application behavior changing without prior notice
- Limited access to backend systems
- No access to the application database
- Test accounts having predefined behaviors


## 12. Test Approach

Testing will begin with manual functional validation.

Requirements will be mapped to test scenarios and test cases. Test cases will then be executed manually and results recorded as PASS or FAIL.

Defects discovered during execution will be documented with reproduction steps and supporting evidence.

Critical and repetitive regression scenarios will then be selected for automation using Playwright.
