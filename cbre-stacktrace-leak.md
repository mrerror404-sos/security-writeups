# 🟦 CBRE — Verbose API Stack Trace Leak  
### Status: N/A (Closed)  
### Reported by: mrror404-sos 

---

## 📌 Summary
During API reconnaissance on CBRE subdomains, an unauthenticated endpoint returned **full .NET stack traces**, middleware details, and internal class names in JSON format.

This exposes sensitive implementation details that can be used for reconnaissance and targeting internal services.

---

## 🔍 Technical Details
Affected endpoint:

