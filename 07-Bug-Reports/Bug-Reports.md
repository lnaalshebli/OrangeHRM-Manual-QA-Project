# Bug Reports

## Bug Report 001

**Bug ID:** BR-001

**Related Test Case:** TC-013

**Related Scenario:** TS-013

**Title:** Dashboard is displayed after logout when clicking the browser Back button

**Severity:** High

**Priority:** Highest

**Environment:** Desktop / Chrome / Production (Public Demo)

**Status:** Open

**Preconditions:**

- The user is logged in and is on the Dashboard.

**Steps to Reproduce:**

1. Click the user profile icon.
2. Click the Logout option.
3. Click the browser Back button.

**Expected Result:**

The Dashboard should not be displayed, and the user should remain on or be redirected to the Login page.

**Actual Result:**

The Dashboard was displayed after logout via the Back button. Clicking any item redirected the user to the Login page.
