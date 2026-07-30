# Registration Test Cases

## Test Case 1: Successful Registration

Test ID: TC_REG_001

### Scenario: User can create a new account with valid information and accepts Terms and Conditions.

Steps:
1. Open registration page
2. Enter valid name
3. Enter valid email
4. Enter valid password
5. Check the Terms and Conditions checkbox
6. Click Register button

Result:
User account is created successfully.

Status: Pass

## Test Case 2: Registration with existing email

Test ID: TC_REG_002

### Scenario: User cannot create an account with an email that already exists.

Steps:
1. Open registration page
2. Enter an email that is already registered
3. Enter valid password
4. Check the Terms and Conditions checkbox
5. Click Register button

Result:
An error message is displayed that the email is already in use.

Status: Pass


## Test Case 3: Registration with empty fields

Test ID: TC_REG_003

### Scenario: User cannot register without filling in required fields.

Steps:
1. Open registration page
2. Leave required fields empty
3. Click Register button

Result:
Validation messages are displayed and the account is not created.

Status: Pass


## Test Case 4: Registration with invalid email

Test ID: TC_REG_004

### Scenario: User cannot register with an invalid email format.

Steps:
1. Open registration page
2. Enter an invalid email
3. Enter a valid password
4. Check the Terms and Conditions checkbox
5. Click Register button

Result:
An error message is displayed asking for a valid email address.

Status: Pass


## Test Case 5: Registration without accepting Terms and Conditions

Test ID: TC_REG_005

### Scenario: User cannot create an account without accepting Terms and Conditions.

Steps:
1. Open registration page
2. Enter valid name
3. Enter valid email
4. Enter valid password
5. Do not check the Terms and Conditions checkbox
6. Click Register button

Result:
User cannot create an account and a message is displayed asking to accept Terms and Conditions.

Status: Pass
