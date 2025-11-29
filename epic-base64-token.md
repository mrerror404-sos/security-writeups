
---

# 📄 **FILE 2 — `epic-base64-token.md`**

```md
# 🔐 Epic Games — Hardcoded Base64 DeviceAuth Token in JavaScript  
### *Status: Informative (Closed)*  
### *Reported by: mrror404-sos | Age: 14*

---

## 📌 Summary
While reviewing JavaScript files related to Epic Games client authentication, I found a **hardcoded Base64-encoded DeviceAuth token** embedded directly in the authentication logic.

Base64 ≠ encryption, therefore any embedded value can be decoded by attackers.

---

## 🧪 Technical Details
The exposed token was located in:

