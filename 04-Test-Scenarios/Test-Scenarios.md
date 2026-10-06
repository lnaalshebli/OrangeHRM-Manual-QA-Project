# Test Scenarios

## 1. Login
- TS-001: Verify login with a valid username and a valid password. 
- TS-002: Verify login with a valid username and an invalid password.
- TS-003: Verify login with an invalid username and a valid password.
- TS-004: Verify login with an invalid username and an invalid password.
- TS-005: Verify login when the username and password fields are empty. 
- TS-006: Verify login when the username is empty and password is filled. 
- TS-007: Verify login when the username is filled and password is empty.
- TS-008: Verify login with a username using different letter cases.
- TS-009: Verify that the password field masks the entered characters.
- TS-010: Verify that the system displays an error message when login fails.



## 2. Logout
- TS-011: Verify that users can log out from their account.
- TS-012: Verify that the user session ends after logout.
- TS-013: Verify that the user cannot return to the Dashboard using the browser Back button after logout.




## 3. Employee Management

* **TS-014:** Verify that the Employee List displays the expected employee fields.
* **TS-015:** Verify that opening an individual employee's profile displays the expected information.
* **TS-016:** Verify that the Employee List supports pagination when there are many records.
* **TS-017:** Verify that a new employee can be added with the required information.
* **TS-018:** Verify that the system handles adding an employee with a duplicate Employee ID.
* **TS-019:** Verify that entered data is not saved when the user cancels the Add Employee form.
* **TS-020:** Verify that the system provides appropriate confirmation or navigation after successfully adding a new employee.
* **TS-021:** Verify that the system displays validation errors when required employee information is missing.
* **TS-022:** Verify that authorized users can edit existing employee information.
* **TS-023:** Verify that authorized users can search for employees using the available search criteria.
* **TS-024:** Verify that search results display the expected matching employee(s).
* **TS-025:** Verify that the search supports partial matches.
* **TS-026:** Verify whether the search is case-sensitive.
