# Bug Reports - Sauce Demo Application

## Application: https://www.saucedemo.com

---

## BUG-001 - Login button does not respond on empty fields (example format)

**Title:** Login button allows submission with empty fields without proper validation

**Environment:**
- Browser: Chrome (latest)
- OS: Windows / macOS (specify if needed)

**Severity:** Medium  
**Priority:** High  

---

### Description:
When the user clicks the Login button without entering username and password, the system does not clearly enforce validation in a user-friendly way.

---

### Steps to Reproduce:
1. Go to https://www.saucedemo.com
2. Leave username empty
3. Leave password empty
4. Click Login

---

### Expected Result:
System should display clear validation message:
"Username is required"

---

### Actual Result:
Error handling is not clearly triggered or user feedback is unclear.

---

### Status:
Open

---

## BUG-002 - Error message appears when logging in with invalid credentials

**Title:** Incorrect error message displayed for invalid login attempt

**Severity:** Low  
**Priority:** Medium  

---

### Description:
When entering invalid credentials, the system shows a generic error message instead of a more descriptive validation response.

---

### Steps to Reproduce:
1. Enter username: wrong_user
2. Enter password: wrong_password
3. Click Login

---

### Expected Result:
Clear authentication failure message:
"Username and password do not match"

---

### Actual Result:
Generic or inconsistent error message displayed.

---

### Status:
Open

---

## BUG-003 - Password field accepts visible input (UI/UX issue)

**Title:** Password field does not clearly mask input in all cases

**Severity:** Low  
**Priority:** Low  

---

### Description:
Password input visibility may not consistently behave as expected across browsers.

---

### Steps to Reproduce:
1. Open login page
2. Enter password in password field
3. Observe input behavior

---

### Expected Result:
Password should be masked (••••••)

---

### Actual Result:
Password visibility may not behave consistently depending on browser behavior.

---

### Status:
Open
