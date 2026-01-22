# Intentionally Vulnerable Flask Web Application

## Overview
This project is a **custom intentionally vulnerable web application** developed using **Python Flask** for learning and demonstrating web security vulnerabilities based on the **OWASP Top 10**.

⚠️ This application is insecure by design and must only be used in a controlled lab environment.

---

## Environment
- OS: Kali Linux
- Framework: Python Flask

---

## Vulnerability Assessment
The application was assessed using both manual testing and automated tools.

### Tools Used
- Nmap  
  `nmap -sV -p 5000 127.0.0.1`
- Nikto  
  `nikto -h http://127.0.0.1:5000`

---

## Identified Vulnerabilities
- SQL Injection (OWASP A03)
- Cross-Site Scripting (XSS) (OWASP A03)
- Broken Authentication (OWASP A07)
- Command Injection (OWASP A03)
- Security Misconfiguration (OWASP A05)


---

## Disclaimer
This project is strictly for **educational purposes only**. Do not deploy in production environments.
