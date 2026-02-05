# Login Functionality – Test Cases

## Test Case ID: TC_LOGIN_001
**Title:** Successful login with valid credentials  
**Priority:** High  
**Severity:** Critical  

### Preconditions:
- User has a registered account
- Login page is accessible
- Browser is opened

### Test Steps:
1. Open the login page
2. Enter a valid email address
3. Enter a valid password
4. Click the "Login" button

### Expected Result:
- User is successfully logged in
- User is redirected to the dashboard or main page
- No error messages are displayed

---

## Test Case ID: TC_LOGIN_002
**Title:** Login with invalid password  
**Priority:** High  
**Severity:** Major  

### Preconditions:
- User has a registered account
- Login page is accessible

### Test Steps:
1. Open the login page
2. Enter a valid email address
3. Enter an invalid password
4. Click the "Login" button

### Expected Result:
- User is not logged in
- Error message is displayed: "Invalid email or password"
- User remains on the login page

---

## Test Case ID: TC_LOGIN_003
**Title:** Login with empty fields  
**Priority:** Medium  
**Severity:** Minor  

### Preconditions:
- Login page is accessible

### Test Steps:
1. Open the login page
2. Leave email field empty
3. Leave password field empty
4. Click the "Login" button

### Expected Result:
- User is not logged in
- Validation messages are displayed for required fields
- Login button does not proceed authentication
