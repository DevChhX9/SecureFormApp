# ✅ ComplianceChecklist.md – Mapping Features to Standards

| Compliance Standard | Requirement | Covered Feature | Notes |
|---------------------|-------------|------------------|-------|
| **GDPR** | Right to access/delete personal data | "Delete My Data" button | Simulates user-triggered deletion |
| **GDPR** | Minimal data collection | Simple display only (name, email) | No unnecessary info stored |
| **HIPAA** | Role-based access to sensitive data | Role dropdown in login | Could simulate role-restricted pages |
| **PCI-DSS** | Masked credit card input | Payment form with masked card number | Should limit visibility of digits |
| **PCI-DSS** | CVV not stored or shown | CVV input field (not retained) | Should never save CVV values |
| **General Security** | 2FA authentication | Login form with 2FA field | Manual code entry simulates auth |
| **General QA** | Input validation and error handling | Forms for login/payment | Prevents invalid data submissions |

---

This checklist maps key compliance goals to actual app features to help recruiters or employers understand your awareness of QA for regulated environments.
