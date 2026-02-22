# FUTURE_CS_01
# Task 1: Web Vulnerability Assessment Report
**Internship:** Cyber Security - Future Interns  
**ID:** [FIT/FEB26/CS6331]  
**Target Application:** http://testphp.vulnweb.com

## 📌 Project Overview
The objective of this task was to perform a professional-grade vulnerability assessment on a web application. Using industry-standard security tools, I identified critical configuration gaps and provided business-oriented remediation strategies to harden the application's security posture.

## 🛠️ Security Tools Used
* **Nmap:** Utilized for network mapping, service discovery, and identifying open ports.
* **OWASP ZAP:** Employed for passive web application scanning to detect security misconfigurations without disrupting services.
* **Canva:** Used to generate a high-quality, professional report for business stakeholders.
* **Broser Developer Tools** Used to extract the cookies and satatus codes and requests and responses.

## 🛡️ Key Findings & Risk Analysis
I identified four primary security vulnerabilities during the assessment:

1.  **Missing Anti-Clickjacking Header (X-Frame-Options):** (Medium Risk) - Vulnerable to UI redressing attacks.
2.  **Absence of Anti-CSRF Tokens:** (Medium Risk) - Risk of unauthorized state-changing actions on behalf of users.
3.  **X-Content-Type-Options Header Missing:** (Low Risk) - Prone to MIME-sniffing exploits.
4.  **HSTS Header Not Set:** (Low Risk) - Application does not enforce encrypted HTTPS connections.

## 🚀 Conclusion
This assessment highlights the importance of "Defense-in-Depth." By implementing the suggested HTTP security headers and CSRF protections, the application can significantly reduce its attack surface and protect user sessions.
