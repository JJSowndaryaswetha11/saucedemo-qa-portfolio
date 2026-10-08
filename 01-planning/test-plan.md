# Test Plan

## 1. Document Information

| Field | Details |
|---|---|
| Project | SauceDemo Manual QA Testing |
| Application | SauceDemo |
| Application URL | https://www.saucedemo.com/ |
| Document | Test Plan |
| Testing Type | Manual Testing |
| Prepared By | Sowndarya Swetha |
| Version | 1.0 |
| Status | Planned |

---

## 2. Test Objective

The objective of this test plan is to define the approach, scope, resources, environment, and activities required to perform manual testing of the SauceDemo web application.

The testing will verify that the application's major functional workflows operate as expected and that identified defects are properly documented, retested, and tracked through closure.

---

## 3. Application Overview

SauceDemo is a web-based e-commerce application that allows users to:

- Log in using provided user accounts.
- Browse available products.
- Sort products.
- View product details.
- Add and remove products from the shopping cart.
- Proceed through checkout.
- Complete an order.
- Navigate through the application's sidebar.
- Use application state management features.
- Access the application's footer and external links.

The application provides multiple user accounts with different behaviors, which will be considered during testing.

---

## 4. Scope

### 4.1 In Scope

The following areas are included in testing:

- Login and authentication
- Logout and session behavior
- Products and inventory
- Product sorting
- Product details
- Shopping cart
- Checkout
- Order completion and confirmation
- Sidebar and navigation
- Dynamic Catalog
- Application state management
- Footer and external links
- Input validation
- End-to-end shopping workflows
- Defect reporting
- Retesting
- Regression testing

### 4.2 Out of Scope

The following areas are outside the scope of this project:

- Backend/source-code testing
- Database testing
- Payment gateway integration with a real payment provider
- Production deployment testing
- Load and stress testing using performance-testing tools
- Accessibility certification
- Security penetration testing
- Third-party systems beyond basic external-link verification

---

## 5. Testing Approach

Testing will follow a structured manual testing process:

1. Analyze application functionality and requirements.
2. Define test scenarios.
3. Design detailed test cases.
4. Prepare test data.
5. Execute test cases.
6. Record actual results and execution status.
7. Report confirmed defects.
8. Retest resolved defects.
9. Perform regression testing on affected functionality.
10. Prepare test summary and closure documentation.

Both positive and negative testing will be performed where applicable.

Different SauceDemo user accounts will be used according to the functionality and behavior being tested.

---

## 6. Testing Types

The following testing types will be performed where applicable:

- Functional Testing
- UI Testing
- Positive Testing
- Negative Testing
- Validation Testing
- Integration-oriented Workflow Testing
- Regression Testing
- Retesting
- Compatibility-oriented Testing
- Exploratory Testing

---

## 7. Test Environment

| Item | Details |
|---|---|
| Application | SauceDemo |
| Environment | Web |
| Browser | Google Chrome |
| Operating System | Windows |
| Testing Type | Manual |
| Network | Internet connection |
| Application URL | https://www.saucedemo.com/ |

Browser DevTools may be used during testing for basic troubleshooting, inspection, and supporting evidence.

---

## 8. Test Data

The testing will use the user accounts provided by SauceDemo.

### User Accounts

- `standard_user`
- `locked_out_user`
- `problem_user`
- `performance_glitch_user`
- `error_user`
- `visual_user`

Additional test data such as:

- Valid checkout information
- Invalid checkout information
- Empty fields
- Whitespace values
- Invalid login inputs

will be prepared as required by individual test cases.

Detailed test data will be maintained separately in:

`03-test-design/test-data.md`

---

## 9. Entry Criteria

Testing will begin when:

- The application is accessible.
- Required user accounts are available.
- The test environment is ready.
- Requirements and test scenarios have been defined.
- Test cases are prepared and reviewed.
- Required test data is available.

---

## 10. Exit Criteria

Testing will be considered complete when:

- Planned test cases have been executed.
- Test execution results have been recorded.
- Confirmed defects have been documented.
- Critical test flows have been completed.
- Reported defects have been retested where applicable.
- Regression testing has been completed for affected areas.
- Test results and metrics have been documented.
- Test summary and closure documentation have been prepared.

---

## 11. Defect Management

Confirmed defects identified during testing will be documented with:

- Defect ID
- Summary
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Evidence
- Retest Result

Defects will be classified according to their impact and urgency.

Only defects confirmed through testing will be included in the defect reports.

---

## 12. Test Deliverables

The following deliverables will be maintained as part of the project:

- Test Plan
- Requirements
- Requirements Traceability Matrix
- Test Scenarios
- Test Cases
- Test Data
- Test Execution Log
- Defect Reports
- Test Evidence
- Retesting and Regression Results
- Test Summary Report
- Test Closure Report
- Job Work Sample

---

## 13. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Application behavior may differ between user accounts | Execute relevant scenarios using appropriate user accounts |
| Application behavior may change during testing | Record the tested application behavior and environment |
| Intermittent application behavior | Repeat the test and capture supporting evidence before reporting a defect |
| Insufficient test data | Prepare test data before execution |
| Defects may affect subsequent testing | Record defects and retest affected functionality after resolution |
| External links may change independently of the application | Verify the destination and record the observed behavior during testing |

---

## 14. Test Schedule

Testing activities will be performed in the following sequence:

| Phase | Activity |
|---|---|
| Phase 1 | Requirement Analysis |
| Phase 2 | Test Planning |
| Phase 3 | Test Scenario Design |
| Phase 4 | Test Case Design |
| Phase 5 | Test Data Preparation |
| Phase 6 | Test Execution |
| Phase 7 | Defect Reporting |
| Phase 8 | Retesting |
| Phase 9 | Regression Testing |
| Phase 10 | Test Summary and Closure |

---

## 15. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Tester | Requirement analysis, test design, test execution, defect reporting, retesting, regression testing, and documentation |
| Developer | Investigate and resolve confirmed defects |
| QA Tester / Reviewer | Review test results and verify defect fixes |

---

## 16. Approval

| Role | Name | Status |
|---|---|---|
| QA Tester | Sowndarya Swetha | Prepared |
