🔐 Vulnerability Assessment Report

🌐 Target Website

demo.testfire.net

---

📖 Project Overview

This repository contains a security assessment of a web application performed as part of a cybersecurity internship task.

The objective of this assessment is to identify:

- Exposed services
- Security misconfigurations
- Web application vulnerabilities
- Client-side weaknesses

The analysis was conducted in a read-only and non-intrusive manner, without exploiting any vulnerabilities.

---

🎯 Scope of Assessment

- Only publicly accessible components were tested
- No authentication bypass or active exploitation was performed
- Focus was on identifying and documenting security issues

---

🛠️ Tools Used

- Nmap – Network scanning and port discovery
- OWASP ZAP – Web vulnerability scanning
- Browser Developer Tools – Manual inspection of frontend behavior

---

🔍 Assessment Methodology

1. Network Analysis (Nmap)

- Identified open ports and services
- Detected exposed network entry points

2. Vulnerability Scanning (OWASP ZAP)

- Detected common web vulnerabilities
- Identified missing security headers
- Analyzed session and cookie behavior

3. Client-Side Analysis (DevTools)

- Inspected HTML, JavaScript, and forms
- Checked for exposed data and weak configurations

---

🌐 Key Findings

🔴 High Risk

- Unsecured HTTP communication
- Multiple open ports increasing attack surface
- Exposure of intentionally vulnerable application

🟠 Medium Risk

- Missing security headers (CSP, X-Frame-Options)
- Absence of CSRF protection
- Potential SSL/TLS misconfiguration

🟡 Low Risk

- Cookie security weaknesses
- Server version disclosure
- JavaScript information exposure

🔵 Informational

- Comments and minor information disclosure
- Session handling observations

---

📊 Risk Summary

Risk Level| Count
High| 3
Medium| 4
Low| 4
Informational| 2

---

📂 Repository Structure

📁 report/
   └── Vulnerability_Assessment_Report.pdf

📁 evidence/
   ├── nmap_scan.png
   ├── zap_results.png
   ├── devtools_inspection.png

📄 README.md

---

📄 Report

The complete detailed report is available here:
👉 "/report/Vulnerability_Assessment_Report.pdf"

---

📸 Evidence

Nmap Scan

"Nmap" (evidence/nmap_scan.png)

OWASP ZAP Results

"ZAP" (evidence/zap_results.png)

DevTools Inspection

"DevTools" (evidence/devtools_inspection.png)

---

🛡️ Recommendations

- Enforce HTTPS across all endpoints
- Implement proper security headers
- Secure cookies with "Secure", "HttpOnly", and "SameSite" attributes
- Remove sensitive information from frontend code
- Limit unnecessary open ports
- Conduct regular vulnerability assessments

---

📌 Conclusion

The assessment highlights multiple security weaknesses across network, application, and client layers.

Although the target is intentionally vulnerable for testing purposes, these findings reflect real-world risks such as:

- Data interception
- Unauthorized access
- Client-side attacks
- System compromise

Addressing these issues will significantly improve the overall security posture.

---
👨‍💻 Author
    R Aravinth

Cybersecurity Intern
