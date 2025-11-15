# 🛡️ PortSwigger Web Security Academy Writeups

Security research notes and exploit demonstrations for PortSwigger Web
Security Academy labs, focused on real‑world vulnerabilities aligned
with the **OWASP Top 10**.

## 📌 Overview

This repository contains structured, technical writeups documenting the
exploitation process for various web security vulnerabilities.\
The goal is to demonstrate practical offensive security skills,
methodology, and understanding of modern web attack surfaces.

Each writeup highlights: - 🔍 Vulnerability identification\
- 🪜 Exploitation steps\
- 🧪 Payloads used\
- 🛠 Technical reasoning\
- 🌐 Mapping to **OWASP Top 10** categories

This repository serves as part of my **cybersecurity portfolio** and
showcases hands‑on experience with web application security testing.

## 🧩 Vulnerability Coverage (Mapped to Repository Structure)

### 1️⃣ Injection  
📁 **Folder:** `Injection/`  
Includes SQL Injection, Command Injection, XXE Injection, XPath Injection, and other injection-based attack vectors.

---

### 2️⃣ Authentication Issues  
📁 **Folder:** `Authentication/`  
Covers weak authentication flows, session flaws, login bypass techniques, credential brute forcing, and authentication weaknesses.

---

### 3️⃣ Sensitive Data Exposure  
📁 **Folder:** `Crypto/`  
Involves cryptographic failures, insecure storage, weak encryption, and exposure of sensitive information through insecure implementations.

---

### 4️⃣ XXE & SSRF  
📁 **Folder:** `SSRF_XXE/`  
Focuses on XML External Entity attacks, server-side request forgery, and server-side interaction vulnerabilities.

---

### 5️⃣ Broken Access Control  
📁 **Folder:** `Access_Control/`  
Includes IDOR, privilege escalation, path traversal, access bypass, and unauthorized access to protected resources.

---

### 6️⃣ Security Misconfiguration  
📁 **Folder:** `Misconfiguration/`  
Covers insecure server settings, missing or improper headers, CORS misconfigurations, default configurations, and deployment weaknesses.

---

### 7️⃣ Cross-Site Scripting (XSS)  
📁 **Folder:** `XSS/`  
Contains Reflected, Stored, and DOM-Based XSS attacks and other client-side injection techniques.

---

### 8️⃣ Insecure Deserialization  
📁 **Folder:** `Deserialization/`  
Includes vulnerabilities caused by insecure object deserialization leading to unauthorized behavior or possible code execution.

---

### 9️⃣ Using Components with Known Vulnerabilities  
📁 **Folder:** `Notes/`  
Documents cases involving outdated, unpatched, or vulnerable third-party components and libraries.

---

### 🔟 Insufficient Logging & Monitoring  
📁 **Folder:** `Notes/`  
Contains observations where applications fail to log critical actions, anomalies, or malicious behavior effectively.


## 📁 Repository Structure

    PortswiggerLabs-Writeups/
    │
    ├── Injection/
    ├── Authentication/
    ├── Access_Control/
    ├── XSS/
    ├── SSRF_XXE/
    ├── Misconfiguration/
    ├── Crypto/
    ├── Deserialization/
    └── Notes/

## 🎯 Purpose of This Repository

-   Demonstrate hands‑on experience in offensive security\
-   Show practical knowledge of OWASP Top 10 vulnerabilities\
-   Present a structured approach to exploit development\
-   Serve as a portfolio component for cybersecurity roles

## 🤝 Contributions

This repository is primarily part of my personal security portfolio.\
External contributions are currently limited, but suggestions are
welcome.

## ⭐ Support

If you find the work useful or relevant, feel free to ⭐ star the
repository.
