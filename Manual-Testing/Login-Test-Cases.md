# Login Test Cases – SauceDemo

**Application:** https://www.saucedemo.com/

**Module:** Login

**Test Type:** Functional, Negative, and Boundary Testing

**Execution Status:** Not Executed

## Test Scenarios

- Verify successful login with valid credentials.
- Verify login behavior with invalid credentials.
- Verify required field validation.
- Verify login behavior for a locked-out user.
- Verify password field masking.

## Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result |
|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | Enter a valid username and password, then click Login. | User is redirected to the inventory page. |
| TC_LOGIN_002 | Login with invalid password | Enter a valid username and an invalid password, then click Login. | An appropriate error message is displayed and login is rejected. |
| TC_LOGIN_003 | Login with invalid username | Enter an invalid username and a valid password, then click Login. | An appropriate error message is displayed and login is rejected. |
| TC_LOGIN_004 | Login with empty username | Leave username empty, enter a password, then click Login. | A username-required validation message is displayed. |
| TC_LOGIN_005 | Login with empty password | Enter a username, leave password empty, then click Login. | A password-required validation message is displayed. |
| TC_LOGIN_006 | Login with both fields empty | Leave username and password empty, then click Login. | Login is rejected with a required-field validation message. |
| TC_LOGIN_007 | Login with locked-out user | Enter the locked-out user credentials, then click Login. | Login is rejected with an appropriate locked-out message. |
| TC_LOGIN_008 | Verify password masking | Enter a password and observe the password field. | Password characters are masked. |

## Execution Notes

These test cases are prepared for manual execution against the SauceDemo demo application. Actual results, execution statuses, and any defects will be documented after testing.
