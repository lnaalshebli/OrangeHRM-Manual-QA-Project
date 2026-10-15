# Test Plan

## 1. Objective

The objective of this project is to test the main functionalities of OrangeHRM using manual functional testing. The testing focuses on verifying expected behavior, checking input validation, and identifying functional defects.

## 2. Scope

### In Scope
- Login with valid and invalid credentials.
- Login validation and error messages.
- Logout functionality.
- Admin/User List functionality.
- Employee Management (PIM), including:
  - Adding new employees.
  - Validating required fields.
  - Checking duplicate Employee IDs.
  - Viewing and editing employee information.
  - Searching for employees by Employee ID and name.
  - Testing partial-match and case-insensitive search.
  - Checking employee list fields and pagination.

### Out of Scope
- Performance testing.
- Security testing.
- Role-based access testing.
- Deleting employees.
- Other modules, such as Leave, Time, and Recruitment.

## 3. Test Approach

- Perform manual functional testing.
- Prepare test cases based on requirements, requirement analysis, and test scenarios.
- Cover positive and negative test cases.
- Compare actual results with expected results.
- Report confirmed defects in Jira.
- Record test results and attach screenshots when needed.

## 4. Test Environment

- **Application:** OrangeHRM Demo.
- **Device:** Desktop computer.
- **Operating System:** Windows 11.
- **Browser:** Google Chrome.
- **Environment Type:** Public Demo Environment.

**Note:** The demo environment is shared with other users, so its data and behavior may change.

## 5. Tools

- **GitHub:** Store project documentation.
- **Jira:** Report and track defects.
- **Google Sheets:** Prepare and organize test cases and test results.
- **CSV:** Export test cases for project documentation.
- **Google Chrome:** Access and test the application.

## 6. Entry and Exit Criteria

### Entry Criteria
- Requirements and requirement analysis are prepared.
- Test scenarios and test cases are documented.
- The application is accessible.
- Required test data is available.

### Exit Criteria
- Test results are recorded for the executed test cases.
- Failed test cases are reviewed.
- Confirmed defects are documented in Jira.
- Blocked or unexecuted test cases are recorded.
- Test execution results are documented.

## 7. Test Deliverables

- Requirements Document.
- Requirement Analysis Document.
- Test Scenarios.
- Test Cases.
- Test Execution Report.
- Bug Reports.
- Test Summary Report.

## 8. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Demo data may be changed by other users. | Record test results and capture screenshots during execution. |
| Testing may modify existing employee data. | Use dedicated test employees whenever possible and restore modified data when practical. |
| The demo site may become unavailable or reset. | Record the execution date and repeat affected tests when possible. |
| Application behavior may change. | Verify unexpected behavior and record evidence before reporting a defect. |

## 9. Assumptions and Constraints

- Testing is performed using the available demo account.
- The demo environment may have shared data and limitations.
- Testing is limited to the features listed in the scope.
- All testing in this project phase is performed manually.
- Results reflect the behavior observed during test execution.

## 10. Test Data

- **Login:** Demo credentials provided by the application.
- **Employee Management:** Test employee records used for adding, editing, and searching.
- **Validation:** Empty required fields and duplicate Employee IDs.
- **Search:** Employee IDs, full names, partial names, and different letter cases.

## 11. Defect Management

Unexpected results are reviewed to determine whether they represent actual defects.

Confirmed defects are documented in Jira with the following details:
- Bug title and description.
- Steps to reproduce.
- Expected result.
- Actual result.
- Severity and priority.
- Test environment.
- Screenshots or other supporting evidence, when available.

## 12. Project Status

This document describes the scope and approach for the OrangeHRM manual testing project. Test execution results and the overall testing status are documented separately in the Test Execution Report and Test Summary Report.
