Task 1 – Future Interns Cyber Security Internship
 About the Task
        This project is part of my Cyber Security Internship where I performed a vulnerability assessment on a live web application.
🌐 Target Website
       URL: http://testphp.vulnweb.com⁠�
       Type: Vulnerable Demo Application
Tools Used
    Nmap
    OWASP ZAP
    Browser Developer Tools
Methodology :
    Explored the website manually
    Performed scanning using OWASP ZAP
    Identified vulnerabilities 

Classified risks based on severity
⚠️ Key Vulnerabilities
🔴 SQL Injection (High)
    Input fields are not secure
    Can access database
🔴 Cross Site Scripting (XSS) (High)
    User input not sanitized
    Script injection possible
🟠 Missing Security Headers (Medium)
    Security headers not configured
🟡 Information Disclosure (Low)
    Server details exposed
Risk Summary :
    High → SQL Injection, XSS
    Medium → Security Headers
    Low → Information Disclosure 
Recommendations :
    Validate user input
    Use HTTPS
    Add security headers
    Perform regular testing
 Skills Learned :
    Vulnerability Assessment
    Security Tools Usage
    Risk Analysis
Conclusion :
  This task helped me understand real-world vulnerabilities and how to identify them using tools like OWASP ZAP.
 by:
      Aravinth R
      Cyber Security Intern
