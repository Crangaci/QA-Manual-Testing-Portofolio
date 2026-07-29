# Login Test Cases

## Test Case 1: Successful Login

Test ID: TC_LOGIN_001

### Scenario: User can login with valid credentials.

Steps:
1. Open login page
2. Enter valid email
3. Enter valid password
4.Click Login button

Result:
User successfully logs into the account.

Status: Pass

## Test Case 2: Login with incorrect password

Test ID: TC_LOGIN_002

### Scenario: User cannot login with an invalid password.

Steps:
1. Open login page
2. Enter valid email
3. Enter incorrect password
4. Click Login button

Result:
Error message is displayed.

Status: Pass

## Test Case 3: Login with empty fields

Test ID: TC_LOGIN_003

### Scenario: User cannot login without entering an email and password.

Steps:
1. Open the login page.
2. Leave the email and password fields empty.
3. Click the Login button.

Result:
The user cannot log in, and a message asks them to fill in the required fields.

Status: Pass

## Test Case 4: Login with invalid email

Test ID: TC_LOGIN_004

### Scenario: Login with an invalid email address.

Steps:
1. Open login page
2. Enter invalid email
3. Enter valid password
4. Click Login button

Result:
Error message is displayed.

Status: Pass

## Test Case 5: Logout after successful login

Test ID: TC_LOGIN_005

### Scenario: User can log out after successful login.

Steps:
1. Open login page
2. Enter valid email and password
3. Click Login button
4. Click Logout button

Expected Result:
User is logged out successfully and redirected to the login page.

Status: Pass
