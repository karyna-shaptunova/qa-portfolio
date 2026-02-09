### TC-01: Login with valid credentials
**Preconditions:** 
- User is not logged in
- User is on login page  
**Type:** Functional
**Steps:**
1. Enter valid username
2. Enter valid password
3. Click Login button
**Expected Result:** User is successfully logged in and redirected to the main page

### TC-N-01: Login with invalid username
**Preconditions:** 
- User is not logged in
- User is on login page
**Type:** Negative  
**Steps:**
1. Enter invalid username
2. Enter valid password
3. Click Login button
**Expected Result:** User is not logged in and sees the error message

### TC-N-02: Login with invalid password
**Preconditions:** 
- User is not logged in
- User is on login page
**Type:** Negative  
**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click Login button
**Expected Result:** User is not logged in and sees the error message



