# 🔐 Epic Games — OAuth Client Secret Leak in Public GitHub Repository  
### *Status: Informative (Closed)*  
### *Reported by: mrror404-sos | Age: 14*

---

## 📌 Summary
During passive reconnaissance and GitHub source code analysis, I discovered **exposed OAuth DeviceAuth client credentials** in a public repository associated with Epic Games tooling.

The leaked values included:

- `DEVICE_AUTH_CLIENT_ID`
- `DEVICE_AUTH_CLIENT_SECRET`

These values can be used to impersonate legitimate Epic clients and interact with device authorization flows.

All findings were obtained **non-intrusively** and without interacting with Epic's production systems.

---

## 🧪 Technical Details
The exposed secrets were located inside a TypeScript configuration file:

