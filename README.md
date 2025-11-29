# security-writeups
A collection of my cybersecurity findings, bug bounty write-ups, and security research notes.  14-year-old learner building skills in web security, recon, API testing, cloud misconfigurations, and ethical hacking.

# 🔐 Cybersecurity Writeups & Research  
### *by mrror404-sos — 14-year-old cybersecurity learner*

Welcome to my collection of security writeups, bug bounty findings, and reconnaissance notes.  
I'm **14 years old**, not the topper of my class, not from the “smartest” section, and not someone who gets good marks…

But I’m someone who loves **breaking things safely, understanding systems, and finding vulnerabilities that even adults miss**.

While people laugh at me and compare me with toppers,  
I’m quietly building skills that actually matter.

---

## 🚀 About Me
- 🧠 14-year-old ethical hacker & cybersecurity learner  
- 🔍 Passionate about recon, JS analysis, API testing & cloud misconfig detection  
- 🐞 Found multiple real vulnerabilities across big platforms  
- 📚 Not the best at school marks — but great at understanding how the internet works  
- 🛡️ Learning daily, even when people underestimate me  
- 🎯 Goal: Become a professional penetration tester / security researcher  

---

## 🧰 Skills & Areas of Learning
- Web application security  
- Bug bounty hunting  
- Recon automation  
- GitHub secret scanning  
- JavaScript analysis  
- OAuth & authentication flows  
- API security testing  
- Misconfiguration hunting  
- Clickjacking / CSP findings  
- Cloud key exposure / secret leaks  

---

## 📂 Writeups

### 🟣 **Epic Games — OAuth Client Secret Leak (Informative)**
Exposed `DEVICE_AUTH_CLIENT_ID` & `DEVICE_AUTH_CLIENT_SECRET` in a public GitHub repo.  
Risk: Client impersonation, OAuth abuse, account enumeration.  
➡️ **[Read Writeup](epic-oauth-leak.md)**

---

### 🟣 **Epic Games — Base64 Hardcoded DeviceAuth Token**
Base64 encoded DeviceAuth token found in JS file.  
Risk: Unauthorized device authorization / session spoofing.  
➡️ **[Read Writeup](epic-base64-token.md)**

---

### 🔵 CBRE — Verbose API Stack Trace Leakage (N/A)
Unauthenticated API returning .NET SSO stack trace with internal middleware names.  
➡️ **[Read Writeup](cbre-stacktrace-leak.md)**

---

### 🟢 OneZero Bank — Clickjacking / Missing X-Frame-Options (N/A)
Bank website allowed full framing → clickjacking risk on public pages.  
➡️ **[Read Writeup](bank-clickjacking.md)**

---

### 🟡 Truzta QA — Multi-Service API Keys in JS
Found Twilio, Heroku, Google Captcha, Square tokens in frontend JS bundles.  
➡️ **[Read Writeup](truzta-multi-key-exposure.md)**


---

## 🌟 Why I Do This
I may not be the “smart” student in school.  
Teachers sometimes laugh, friends compare me with toppers,  
but I’m learning something **bigger than marks**:

> **How to secure systems  
> How to find vulnerabilities  
> How to become someone in the future**

This is my journey — and this repository is the proof.

---

## 📫 Contact
If you want to connect or collaborate:

**GitHub:** *this profile*  
**Email:** mrror40476@gmail.com

---

### ❤️ Thanks for visiting my writeups!  
### More vulnerabilities & research coming soon…
