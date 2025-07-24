# 📋 TestCases.md – Compliance-Oriented QA Test Scenarios

## 1. Login Page

### ✅ TC01: Valid Login Input
- **Description:** Ensure form accepts valid username, password, 2FA code
- **Expected Result:** Redirect or confirmation message

### ✅ TC02: Role Selection Behavior
- **Description:** Test different role dropdowns (User/Admin)
- **Expected Result:** Different page access or restrictions (if implemented)

### ✅ TC03: 2FA Code Validation
- **Description:** Leave 2FA field blank or enter invalid input
- **Expected Result:** Error shown or login denied

## 2. My Data Page (GDPR)

### ✅ TC04: View Personal Data
- **Description:** Ensure personal info is correctly displayed
- **Expected Result:** Static name/email loads without error

### ✅ TC05: Delete My Data
- **Description:** Click 'Delete My Data' button
- **Expected Result:** Simulated success message; info cleared or hidden

## 3. Payment Form (PCI-DSS)

### ✅ TC06: Credit Card Input Masking
- **Description:** Ensure credit card input displays masked value
- **Expected Result:** Format as **** **** **** 1234

### ✅ TC07: CVV Length Validation
- **Description:** Enter invalid CVV (e.g., too short)
- **Expected Result:** Error or no submission

### ✅ TC08: Expiration Date Format
- **Description:** Enter various invalid date formats (e.g. 13/99, text)
- **Expected Result:** Error message shown

---

✅ Use these test cases during manual testing or interviews to explain your thought process in testing for compliance, input validation, and access control.
