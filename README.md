# Web Application Security Testing Report
## CYBER SECURITY INTERNSHIP TASK 1

**AUTHOR:** VAIBHAV MALHOTRA  
**TRACK CODE:** FUTURE_CS_01

This repository presents a comprehensive security testing report for a sample web application using DVWA (Damn Vulnerable Web Application) & OWASP JUICE SHOP to identify vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), and Authentication flaws in a controlled lab setup to enhance understanding of real-world web security threats and their mitigations.

---
### 🧠 **Skills Practiced**
1. Vulnerability Analysis (SQLi, XSS, Brute Force)  
2. Ethical Hacking & Penetration testing
3. HTTP Request/Response Analysis using Burp Suite
4. Web Application Security Assessment

### 🧰 **Tools & Testing Platforms**
1. **Tools:** Burp Suite, cutome made wordlists
2. **Testing Platforms:** DVWA ( DAMN VULNERABLE WEB APPLICATION ) & OWASP JUICE SHOP
3. **Operating System:** Kali Linux

---

### 🔍 **Report Highlights**
1. **SQL INJECTION:** Extracted user credentials and database details.
2. **Cross-Site Scripting (XSS):** Exploited **Reflected, Stored** XSS vulnerabilities.
3. **Brute Force (Authentication Flaws):** using custom wordlists we bypass login.

---

### 📁 **Contents**
- TASK-1 WEB APPLICATION SECURITY TESTING.pdf:
  Full detailed report of the testing process, including:
  1. Objective of the Task  
  2. Payloads executed
  3. Screenshots of the evidence (POC)
  4. Methodologies used
  5. Final conclusion & recommendation.

---
### :injection **Vulnerabilities Tested**
1. SQL Injection (SQLi):
   - bypass login using sql payload ("'or'1'='1'--")
   - extracted user's credentials and database ( username, MD5 hashed passwords ) by using UNION-based PAYLOADS ( ' UNION SELECT username, password FROM users --)
2. Cross-Site Scripting (XSS):
   - Reflected XSS: It immediately reflects the entered word in the input field, executing the javascript alert
   - Stored XSS: Here, the script is stored directly in the server.
3. Brute-Force Attack:
   - Used Burp Suite Intruder to bypass login attempts using custom wordlists and sniper attack.  
   - Identified weak passwords and lack of rate-limiting protections.

---
### 📖 **Learning Outcomes**
- Real-world experience in offensive security
- Stronger ability to communicate security risks  
- Practical experience using Burp Suite and other security tools and test platforms like DVWA & Owasp Juice shop  
- Logic building  
- Top10 OWASP Vulnerabilities

---

### ⚠️ **Disclaimer**
- This project was conducted in a safe, controlled lab environment using intentionally vulnerable software for educational purposes only.
- Do not attempt these techniques on live or unauthorized systems, as it may be illegal and unethical.

---
Connect with me on :linkedIn (https://www.linkedin.com/in/vaibhav-malhotra-1b893925a/)  
