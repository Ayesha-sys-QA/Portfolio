# 🐞 Bug Report: BUG001_Login_EmptyFields

**Bug ID**: BUG001  
**Title**: Login fails silently when fields are empty – No error message shown  
**Reported by**: Aicha Moustatia  
**Date Reported**: 2025-06-10  
**Severity**: Medium  
**Priority**: High  
**Status**: Open  
**Environment**: Windows 10, Edge v114, `staging.testsite.com`

---

## 🔍 Description
When attempting to log in without entering a username or password, the system does not display the expected error message. The user is simply left on the same page with no visual feedback.

---

## 🧪 Steps to Reproduce

| Step | Action                    |
|------|---------------------------|
| 1    | Open the login page       |
| 2    | Leave both fields empty   |
| 3    | Click the "Login" button  |

---

## ✅ Expected Result
An error message should appear:  
> "Username and password are required."

---

## ❌ Actual Result
No error message is shown. No visual indication of a failed login.

---

## 📎 Attachments
- Screenshot: 
---

## 🔗 Related Test Case
[TC003_Login_EmptyFields](../Test-Cases/TC003_Login_EmptyFields.md)
