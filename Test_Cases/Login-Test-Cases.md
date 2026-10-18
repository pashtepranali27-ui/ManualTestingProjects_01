# Login Test Cases

**Project:** Manual Testing Project – SauceDemo  
**Application:** https://www.saucedemo.com/  
**Module:** Login

| Test Case ID | Test Scenario | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | standard_user / secret_sauce | Products page opens | The Products page opened successfully. | PASS |
| TC_LOGIN_002 | Login with invalid password | standard_user / wrong123 | Error message is displayed | Epic sadface: Username and password do not match any user in this service | PASS |
| TC_LOGIN_003 | Login with empty username | Empty username / secret_sauce | Error message is displayed | Epic sadface: Username is required | PASS |
| TC_LOGIN_004 | Login with empty password | standard_user / Empty password | Error message is displayed | Epic sadface: Password is required| PASS |
| TC_LOGIN_005 | Login with both fields empty | Both fields empty | Error message is displayed | Epic sadface: Username is required | PASS |

## Test Execution Notes

- Execute each test case on the SauceDemo application.
- Record the actual result observed.
- Mark each test case as PASS or FAIL based on the expected result.