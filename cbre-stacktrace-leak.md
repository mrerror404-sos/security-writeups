# 🟦 CBRE — Verbose API Stack Trace Leak  
### Status: N/A (Closed)  
### Reported by: mrror404-sos 

---

## 📌 Summary
During API reconnaissance on CBRE subdomains, an unauthenticated endpoint returned **full .NET stack traces**, middleware details, and internal class names in JSON format.

This exposes sensitive implementation details that can be used for reconnaissance and targeting internal services.

---

## 🔍 Technical Details
Affected endpoint:https://api.aggregate.cbre.com


was returning **full .NET exception data**, including:

- Internal class names  
- Middleware identifiers  
- StackTraceString  
- Source file references  
- Detailed plugin names  

This is **sensitive information disclosure** and significantly increases attack surface.

---

## 🔍 Technical Details

### Example response (redacted):
```json
{
  "ClassName": "System.Exception",
  "Message": "Unauthorized",
  "StackTraceString": "Plugin.AzureSSO.Middleware.AzureSSOMiddleware.Invoke...",
  "Source": "Plugin.Azure.SSO"
}


