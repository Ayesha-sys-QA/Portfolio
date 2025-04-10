# Test Case ID: TC003_Login_EmptyFields

**Title:** Verify login behavior when both Email/Phone and Password fields are left empty  
**Priority:** High  
**Precondition:** User is on the Facebook login page  
**Test Data:**  
- Email/Phone: [Leave blank]  
- Password: [Leave blank]

## 🔎 Steps to Execute:
1. Navigate to https://www.facebook.com  
2. Leave the "Email or phone" field empty  
3. Leave the "Password" field empty  
4. Click the “Log In” button

## ❌ Expected Result:
An error message is displayed:  
> "The email or mobile number you entered isn’t connected to an account."  
OR  
> "Please enter your email or mobile number."

User stays on the login page.

## ✅ Actual Result:


## 🛠️ Status:
Fail
