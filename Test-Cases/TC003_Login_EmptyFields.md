# ❌ Test Case: TC003_Login_EmptyFields

**Title**: Verify that login fails when both username and password fields are empty  
**Module**: User Authentication  
**Author**: Aicha Moustatia  
**Date Executed**: 2025-06-10  
**Priority**: Medium  
**Status**: ✅ Passed (Negative Test Case)

---

## 🔍 Test Scenario
Ensure that an error message is displayed when trying to log in without entering any credentials.

---

## 📌 Preconditions
- User is on the login page  
- Username and password fields are empty  

---

## 🧪 Test Steps & Results

| Step | Action                       | Expected Result                          | Actual Result                        | Status |
|------|------------------------------|-------------------------------------------|---------------------------------------|--------|
| 1    | Navigate to login page       | Login page loads correctly                | Login page loaded                     | ✅     |
| 2    | Leave both fields empty      | No data entered                           | Fields remain empty                   | ✅     |
| 3    | Click "Login" button         | Error message: "Username and password required" | Error message displayed         | ✅     |

---

## ❌ Final Result
**Passed** — login blocked and appropriate error shown for empty fields.

## 🧾 Notes
- Browser: Edge v114  
- OS: Windows 10  
- Test performed on: `staging.testsite.com`  
- Error message displayed as expected below the form
