# Test Cases

TestCase - 01: Login with valid credentials

Preconditions:
      User has a valid account

Steps:
      1. Open login page
      2. Enter valid email
      3. Enter valid password
      4. Click "Login"

Expected Result:
      User is successfully logged in and redirected to dashboard
--------------------------------------------------------------------->

TestCase - 02: Login with invalid password

Preconditions:
      User exists

Steps:
      1. Open login page
      2. Enter valid email
      3. Enter invalid password
      4. Click "Login"

Expected Result:
      Error message is displayed: "Invalid credentials"
-------------------------------------------------------------------->

TestCase - 03: Register new user

Preconditions:
      User is not registered

Steps:
      1. Open registration page
      2. Enter valid data
      3. Click "Register"

Expected Result:
      Account is created successfully
-------------------------------------------------------------------->

TestCase - 04: Empty fields validation

Steps:
      1. Open login page
      2. Leave fields empty
      3. Click "Login"

Expected Result:
      Validation messages appear for required fields
