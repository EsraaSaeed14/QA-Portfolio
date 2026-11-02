# Test Execution Report — SauceDemo Login

## 1. Test Execution Overview

| Field | Details |
|---|---|
| Project | SauceDemo — QA Practice Project |
| Application URL | https://www.saucedemo.com/ |
| Module | Login |
| Testing Type | Manual Functional Testing |
| Test Environment | Web Application |
| Test Execution Date | November 3, 2026 |
| Test Cases Executed | 8 |
| Passed | 8 |
| Failed | 0 |
| Blocked | 0 |
| Not Executed | 0 |

## 2. Test Execution Summary

All eight planned login test cases were executed successfully.

**Execution Results:**
- Total Test Cases: 8
- Passed: 8
- Failed: 0
- Pass Rate: 100%

## 3. Detailed Test Execution Results

| Test Case ID | Test Scenario | Actual Result | Status |
|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | User successfully logged in and the inventory page was displayed. | PASS |
| TC_LOGIN_002 | Login with valid username and invalid password | Login was rejected. Error displayed: "Epic sadface: Username and password do not match any user in this service" | PASS |
| TC_LOGIN_003 | Login with invalid username and valid password | Login was rejected. Error displayed: "Epic sadface: Username and password do not match any user in this service" | PASS |
| TC_LOGIN_004 | Login with empty username | Login was rejected. Error displayed: "Epic sadface: Username is required" | PASS |
| TC_LOGIN_005 | Login with empty password | Login was rejected. Error displayed: "Epic sadface: Password is required" | PASS |
| TC_LOGIN_006 | Login with both fields empty | Login was rejected. Error displayed: "Epic sadface: Username is required" | PASS |
| TC_LOGIN_007 | Login with locked-out user | Login was rejected. Error displayed: "Epic sadface: Sorry, this user has been locked out." | PASS |
| TC_LOGIN_008 | Verify password masking | Password characters were displayed as dots instead of plain text. | PASS |

## 4. Defect Summary

No defects were identified during the execution of these eight login test cases.

## 5. Test Conclusion

The SauceDemo login functionality behaved as expected for all executed scenarios, including valid login, invalid credentials, required-field validation, locked-out user handling, and password masking.

**Final Result: PASS — 8/8 test cases passed.**

## 6. Notes

- Testing was performed manually as part of an independent QA portfolio practice project.
- Test results reflect the observed application behavior during execution.
- This project is not affiliated with SauceDemo or its owners.
