# Test Execution Report


## 1. Execution Details

| Item | Value |
|---|---|
| Application | OrangeHRM Demo (OS 5.9) |
| Environment | Public Demo Environment |
| Browser | Google Chrome |
| Operating System | Windows 11 |
| Execution Date | 15 October 2026 |
| Executed By | Lna Ziad Alshebli |

## 2. Execution Summary

| Module | Total | Passed | Failed |
|---|---:|---:|---:|
| Login / Logout | 13 | 12 | 1 |
| Employee Management (PIM) | 14 | 14 | 0 |
| **Total** | **27** | **26** | **1** |

**Pass Rate:** 96.30%

## 3. Failed Test Cases

| Test Case | Defect ID | Details |
|---|---|---|
| TC-013 | BR-001 / OHQA-1 | After logout, pressing the browser Back button displayed the Dashboard. Clicking any item redirected the user to the Login page. See the Bug Report for details and screenshots. |

## 4. Execution Notes

- TC-013 failed because the Dashboard was displayed after logout when the browser Back button was clicked.
- The behavior observed in TC-013 is documented in Bug Report BR-001 and tracked in Jira as OHQA-1.
- TC-022 changed employee 0562's first name from "Archana" to "Archana Test".
- The demo environment is shared with other users, and its data may be reset periodically.
- Test results reflect the behavior observed during execution.

## 5. Evidence

Screenshots related to BR-001 are available in the `07-Bug-Reports` folder.

## 6. Execution Status

A total of 27 test cases were executed: 26 passed and 1 failed. The failed test case is documented in the Bug Reports section and tracked in Jira.
