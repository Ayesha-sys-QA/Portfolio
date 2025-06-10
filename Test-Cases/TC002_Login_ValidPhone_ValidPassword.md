# ✅ Test Case: TC002_Login_ValidPhone_ValidPassword

**Title**: Verify user can log in using a valid phone number and password  
**Module**: User Authentication  
**Author**: Aicha Moustatia  
**Date Executed**: 2025-06-10  
**Priority**: High  
**Status**: ✅ Passed

---

## 🔍 Test Scenario
Verify that login is successful when a user enters a valid phone number and matching password.

---

## 📌 Preconditions
- User is on the login page  
- User has:
  - Valid phone number: `+41791234567`  
  - Valid password: `Test@1234`

---

## 🧪 Test Steps & Results

| Step | Action                         | Expected Result                        | Actual Result                     | Status |
|------|--------------------------------|-----------------------------------------|------------------------------------|--------|
| 1    | Navigate to login page         | Login page loads correctly              | Login page loaded                  | ✅     |
| 2    | Enter valid phone number       | Phone number accepted                   | Input accepted                     | ✅     |
| 3    | Enter valid password           | Password accepted                       | Input accepted                     | ✅     |
| 4    | Click on "Login" button        | Redirect to dashboard/home              | User redirected successfully       | ✅     |

---

## ✅ Final Result
**Passed** — login via phone number and password is working as expected.

## 🧾 Notes
- Browser: Firefox v118  
- OS: Windows 10  
- Test performed on test environment: `qa.testplatform.com`  

