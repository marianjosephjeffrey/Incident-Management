# 🛡 IBM Clicked Incident Management  

## 📌 Overview  
As part of an **IBM Clicked project**, I conducted a **thorough examination of a simulated security incident** to enhance my **incident management** skills. The project involved analyzing a **phishing attack**, investigating a **malicious file**, and providing **security recommendations** to mitigate future threats.  

## 🛠 Key Contributions  

- 🔍 **Performed a detailed analysis** of a **phishing email attack** targeting an employee.  
- 📜 **Conducted a file hash analysis** on a **malicious attachment**, identifying **potential threats**.  
- 🛡 **Investigated security incidents**, correlating logs and evidence to determine **attack vectors**.  
- 🔄 **Proposed security enhancements**, including **email security policies, MFA implementation, and endpoint monitoring**.  
- 🎤 **Submitted a comprehensive incident report**, summarizing findings, impact, and mitigation strategies.  
- 🏆 **Report reviewed and graded by a senior security analyst**, ensuring practical industry relevance.  

---

## 🛠 Tools & Technologies Used  

| Category                     | Tools & Technologies |
|------------------------------|----------------------|
| 🔍 SIEM & Log Analysis       | Splunk, IBM QRadar  |
| 📧 Email Security            | Mimecast, Microsoft Defender for Office 365 |
| 🛡 Endpoint Security         | CrowdStrike Falcon, Microsoft Defender ATP |
| 🔄 Incident Response         | IBM Resilient, Cortex XSOAR |
| 🏴‍☠️ Malware Analysis       | VirusTotal, Hybrid Analysis |
| 🔑 Authentication & IAM      | Cisco Duo MFA, Password Policy Enforcement |
| 🚀 Security Awareness        | Phishing Simulations, Employee Training |
| 🗂 File Hash Analysis        | SHA256, MD5sum |
| 📜 Compliance & Best Practices | NIST, CIS Benchmarks |

---

## ⚙️ Sample Analysis  

### 📧 Extracting Email Header Information for Phishing Analysis  
```bash
cat suspicious_email.eml | grep "From:\|To:\|Subject:\|Received:\|Return-Path:"
```
🔍 Checking File Hash for Malware
```bash
sha256sum malicious_file.exe
md5sum malicious_file.exe
```
🛡 Blocking Phishing Domains in Microsoft Defender
```bash
New-TenantAllowBlockListItems -Block -ListType Url -Entries "malicious-site.com"
```
⸻

📋 Final Report & Evaluation

The project concluded with a comprehensive report containing:

✅ Email analysis findings, identifying malicious sender addresses and phishing indicators.
✅ File hash analysis results, detecting known malware signatures and threat intelligence matches.
✅ Incident response workflow, detailing recommended mitigation steps and containment strategies.
✅ Security recommendations, including email filtering, MFA enforcement, and endpoint protection.
✅ Final submission reviewed by a senior security analyst, ensuring industry best practices were followed.

⸻

🎤 Presentation & Impact

I compiled the incident findings into a detailed presentation, highlighting the impact of phishing attacks and the importance of proactive security controls in incident response.

⸻

💬 Have Questions?

Feel free to reach out or open an issue! 🚀🔐
