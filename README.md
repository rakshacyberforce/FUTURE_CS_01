# FUTURE_CS_01

## Vulnerability Assessment Report

### Internship
Future Interns – Cyber Security Internship

### Assessment Type
Passive Vulnerability Assessment

### Target Website
testaspnet.vulnweb.com

### Objective
The objective of this assessment was to identify publicly observable security weaknesses through passive analysis without performing exploitation or intrusive testing.

### Tools Used
- Nmap
- OWASP ZAP
- Browser Developer Tools
- Kali Linux

### Methodology
1. Information Gathering
2. Network Reconnaissance
3. Website Discovery
4. Passive Vulnerability Assessment
5. Security Header Analysis
6. Risk Classification

### Findings Summary

| Finding | Risk Level |
|----------|----------|
| Content Security Policy (CSP) Header Not Set | Medium |
| Missing Anti-Clickjacking Header | Medium |
| Cookie Without SameSite Attribute | Medium |
| Server Version Disclosure | Low |
| X-AspNet-Version Header Disclosure | Low |
| X-Content-Type-Options Header Missing | Low |

### Evidence
- Nmap Scan Screenshot
- OWASP ZAP Site Discovery Screenshot
- OWASP ZAP Findings Screenshot

### Conclusion
Several security configuration weaknesses were identified during the passive assessment. Implementing the recommended controls will improve the overall security posture of the application.

### Author
PATEL KUNJ
