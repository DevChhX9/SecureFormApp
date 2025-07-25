#  BugReport.md – Sample Issues Found During Compliance QA

## BR01: 2FA Field Accepts Non-Numeric Input
- **Page:** Login
- **Severity:** Medium
- **Steps to Reproduce:**
  1. Go to login page
  2. Enter "abcde" in 2FA field
  3. Submit form
- **Expected Result:** Should reject non-numeric values
- **Actual Result:** Accepts input without warning

## BR02: Credit Card Field Accepts Full Unmasked Numbers
- **Page:** Payment Form
- **Severity:** High (PCI Non-compliance)
- **Steps to Reproduce:**
  1. Type full 16-digit number
  2. Observe that it's visible on screen
- **Expected Result:** Input should auto-mask all but last 4 digits
- **Actual Result:** All digits are shown

##  BR03: "Delete My Data" Button Does Not Clear Fields
- **Page:** My Data Page
- **Severity:** Low
- **Steps to Reproduce:**
  1. Click the "Delete My Data" button
  2. Observe no visual change or confirmation
- **Expected Result:** Simulated message should confirm deletion or hide info
- **Actual Result:** Info remains visible

---

These bug reports are simulated but written in real-world QA report format. Use these to show attention to detail and compliance awareness.
