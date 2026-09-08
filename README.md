# Future Interns – Cyber Security Task 1

## Vulnerability Assessment Report for a Live Website

### Target
`demo.testfire.net`

### Assessment Type
Read-Only / Passive Security Assessment

## Objective
To identify observable security weaknesses in a publicly accessible web application, classify their risks, and provide practical remediation recommendations.

## Scope
- Public-facing website pages
- HTTP/HTTPS response headers
- Cookie security attributes
- TLS/certificate observations
- Basic network exposure analysis

## Tools Used
- Nmap
- cURL
- Browser Developer Tools
- OWASP ZAP (Safe/Passive mode)

## Findings

| ID | Finding | Risk |
|---|---|---|
| F-01 | Expired TLS Certificate | Medium |
| F-02 | Security Headers Not Observed | Medium |
| F-03 | HTTP Service / Plaintext Access | Medium |
| F-04 | TCP/8080 Externally Visible | Low |
| F-05 | Server Technology Disclosure | Low |
| F-06 | Cookie Attribute Inconsistency | Low |

## Report

The complete vulnerability assessment report is available here:

**[Vulnerability Assessment Report](Vulnerability_Assessment_Report.pdf)**

## Ethical & Testing Disclaimer

This assessment was conducted as a read-only security review. No exploitation, login bypass, brute-force attacks, denial-of-service testing, or destructive activities were performed.

## Internship
**Future Interns – Cyber Security Internship**  
**Task 1**
