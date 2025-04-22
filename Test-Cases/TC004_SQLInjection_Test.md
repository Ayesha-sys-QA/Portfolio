# 🐞 Test Case – TC004: SQL Injection in Login Field

**Test Objective:**  
To check if the login form is vulnerable to basic SQL injection input.

---

**Test Steps:**  
1. Navigate to the login page of the application.  
2. In the Email or Username field, input the following string:  
   `' OR 1=1 --`  
3. Enter a random or blank value in the Password field.  
4. Click the Login button.

---

**Expected Result:**  
The system should reject the login attempt and display a generic error message, such as "Invalid credentials."

---

**Actual Result:**  
*Pending — test to be performed on a target application or dummy login form.*

---

**Severity:** Medium to High (depends on whether the injection allows bypassing authentication)

**Test Type:** Exploratory Security Test

**Notes:**  
This is a QA-driven security awareness test, not a replacement for full security audits or penetration testing.  
Always ensure tests are performed on environments where permission has been granted.
