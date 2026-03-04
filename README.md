# Web Application Security Testing Lab
![Security](https://img.shields.io/badge/Type-Security%20Lab-red)
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-black)
![Target](https://img.shields.io/badge/Target-OWASP%20Juice%20Shop-orange)
This project documents a basic web application security testing exercise performed on OWASP Juice Shop in a controlled lab environment.

## Objective

The goal of this exercise was to practice identifying common web vulnerabilities and understand how authentication mechanisms can be tested.

## Tools Used

- Kali Linux
- Nmap
- Burp Suite
- OWASP Juice Shop

## Testing Performed

### Network Scanning

Port scanning was performed using Nmap to identify exposed services.

Command used: nmap -sV -sC -p- localhost

### SQL Injection Testing

The login form was tested for SQL Injection vulnerabilities.

Payload used: ' OR 1=1 --

This payload allowed login bypass in the lab environment.

### XSS Testing

Basic XSS payloads were tested but no successful script execution was observed.

## Notes

All testing was performed on OWASP Juice Shop in a local lab environment created for learning purposes.
