# 🔓 DevTown Bootcamp Project – SQL Injection (SQLi)

![SQLi Banner](https://img.shields.io/badge/Project-SQL%20Injection-red?style=flat-square)  
_A hands-on ethical hacking project exploring SQL Injection vulnerabilities and prevention techniques._

## Overview

This project was part of the **DevTown Bootcamp** and focused on understanding, testing, and mitigating one of the most dangerous web vulnerabilities — **SQL Injection (SQLi)**.

As a **Computer Science student**, I joined the bootcamp not as a cybersecurity expert, but as a developer who realized that building secure applications requires a deep understanding of the threats they face.

##  What I Learned

- What is SQL Injection and how it works
- Types of SQLi:  
  - Error-based  
  - Union-based  
  - Boolean-based blind  
  - Time-based blind  
  - Out-of-Band

- Real-world case studies:  
  - 📌 Pulse Secure VPN – CVE-2019-11510  
  - 📌 Drupalgeddon2 – CVE-2018-7600  
  - 📌 Microsoft CryptoAPI Spoofing – CVE-2020-0601  

- Manual testing using payloads (e.g. `' OR 1=1 --`)
- Automated exploitation with **SQLMap**
- Security best practices to prevent SQLi

##  Tools & Resources Used

- 🔗 **Vulnerable Test Website**: [http://testphp.vulnweb.com](http://testphp.vulnweb.com)
- ⚙️ **SQLMap**: Automated SQLi testing tool  
- 📚 MITRE ATT&CK Mapping (T1190)  
- 🛡 OWASP Top 10 Injection Flaws

##  How to Prevent SQL Injection

- Use **Prepared Statements (Parameterized Queries)**
- Apply **Input Validation** and **Whitelisting**
- Use **ORMs** (like Laravel Eloquent)
- Apply **Least Privilege Principle** on DB accounts
- Enable **Web Application Firewalls (WAF)**
- Implement proper **Error Handling** and **Logging**

## 📁 Project Files

- [`Devtown project_compressed.pdf`](./Devtown%20project_compressed.pdf): Full project report
- [`README.md`](./README.md): This file

##  Key Takeaway

> "Cybersecurity isn’t just for ethical hackers — every developer should know how to break things, so they can build them better."

_This project was completed under the guidance of the DevTown Bootcamp instructors and is meant for ethical learning purposes only._

