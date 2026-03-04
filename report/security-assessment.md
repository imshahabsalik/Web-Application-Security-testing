# Security Assessment Report

Target: OWASP Juice Shop  
Environment: Local Lab  
Tester: Shahab Salik  

## Findings

### SQL Injection (Authentication Bypass)
The login functionality was vulnerable to SQL Injection.

Payload used:
' OR 1=1 --

This allowed login bypass and access to the admin account.

### Information Disclosure

A custom header `X-Recruiting` exposed internal application routes.

## Conclusion
This exercise helped practice basic web application testing techniques such as scanning, authentication testing, and vulnerability identification.
