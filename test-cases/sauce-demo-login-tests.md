# Test Cases - Login Functionality (Sauce Demo)

## Application: https://www.saucedemo.com

---

## TC-001 - Login with valid credentials

**Test Objective:** Verify user can log in successfully with valid credentials

**Preconditions:**
- User is on login page

**Test Steps:**
1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login button

**Expected Result:**
User should be redirected to the Products page

**Actual Result:**
(To be filled after execution)

**Status:**
Not Executed

---

## TC-002 - Login with invalid username

**Test Objective:** Verify error message appears for invalid username

**Test Steps:**
1. Enter username: wrong_user
2. Enter password: secret_sauce
3. Click Login button

**Expected Result:**
Error message displayed: "Epic sadface: Username and password do not match"

**Status:**
Not Executed

---

## TC-003 - Login with invalid password

**Test Steps:**
1. Enter username: standard_user
2. Enter password: wrong_password
3. Click Login button

**Expected Result:**
Error message displayed: "Epic sadface: Username and password do not match"

**Status:**
Not Executed

---

## TC-004 - Login with empty fields

**Test Steps:**
1. Leave username empty
2. Leave password empty
3. Click Login button

**Expected Result:**
Error message: "Epic sadface: Username is required"

**Status:**
Not Executed

---

## TC-005 - Login with locked out user

**Test Steps:**
1. Enter username: locked_out_user
2. Enter password: secret_sauce
3. Click Login button

**Expected Result:**
Error message: "Epic sadface: Sorry, this user has been locked out"

**Status:**
Not Executed
