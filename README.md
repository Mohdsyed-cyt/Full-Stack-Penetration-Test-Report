# Full-Stack Penetration Test & Vulnerability Assessment

## Project Overview
This repository contains a comprehensive offensive security engagement targeting an enterprise Linux application environment. The assessment follows the **Penetration Testing Execution Standard (PTES)** and the **OWASP Top 10** framework to identify, exploit, and document critical vulnerabilities.

## Technical Execution & Contributions
As a primary contributor to this collaborative engagement, I focused on the following high-impact attack vectors:
* **Network Exploitation:** Leveraged manual and automated techniques to exploit backdoors in **VSFTPD v2.3.4** and remote command execution (RCE) in **Samba (usermap_script)**.
* **Web Application Auditing:** Performed targeted exploits for **SQL Injection (SQLi)** and **Command Injection** within a DVWA environment to demonstrate data exfiltration and server-side compromise.
* **Post-Exploitation & Privilege Escalation:** Identified and exploited insecure **NFS (no_root_squash)** configurations to elevate access from a low-privilege user to full **Root** (UID 0).

## Methodology & Tools
* **Reconnaissance:** Nmap, Banner Grabbing, Service Enumeration.
* **Exploitation:** Metasploit Framework, Netcat, Manual Payload Crafting.
* **Web Testing:** SQLMap, Burp Suite, Manual Input Validation.
* **Risk Assessment:** Findings categorized using the **CVSS Framework** to prioritize remediation efforts.

## Professional Certifications Applied
* **CompTIA Security+**
* **ISC2 Certified in Cybersecurity (CC)**

---
**View the Full Technical Report:** [Download PDF Here](./Mohdsyed_FullStack_Penetration_Test_Report.pdf)

*Note: This project was a collaborative effort. Technical screenshots and data logs reflect a shared lab environment.*
EOF
