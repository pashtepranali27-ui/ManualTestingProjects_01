# Login Test Cases

**Project:** Manual Testing Project – SauceDemo  
**Application:** https://www.saucedemo.com/  
**Module:** Login

## Login Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | 1. Open SauceDemo. 2. Enter username. 3. Enter password. 4. Click Login. | Username: standard_user; Password: secret_sauce | Products page opens successfully. | The Products page opened successfully. | PASS |
| TC_LOGIN_002 | Login with invalid password | 1. Open SauceDemo. 2. Enter username. 3. Enter an incorrect password. 4. Click Login. | Username: standard_user; Password: wrong123 | An appropriate error message is displayed. | Epic sadface: Username and password do not match any user in this service | PASS |
| TC_LOGIN_003 | Login with empty username | 1. Open SauceDemo. 2. Leave username empty. 3. Enter password. 4. Click Login. | Username: empty; Password: secret_sauce | A username validation message is displayed. | Epic sadface: Username is required | PASS |
| TC_LOGIN_004 | Login with empty password | 1. Open SauceDemo. 2. Enter username. 3. Leave password empty. 4. Click Login. | Username: standard_user; Password: empty | A password validation message is displayed. | Epic sadface: Password is required | PASS |
| TC_LOGIN_005 | Login with both fields empty | 1. Open SauceDemo. 2. Leave both fields empty. 3. Click Login. | Username: empty; Password: empty | A validation message is displayed. | Epic sadface: Username is required | PASS |

## Test Execution Notes

- All five test cases were executed manually.
- Actual results were recorded based on the application behavior observed.
- A test case is marked PASS when the actual result matches the expected result.