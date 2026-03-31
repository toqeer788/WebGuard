# 🛡️ WebGuard v1.0 - The Multi-Tool Web Vulnerability Scanner

![GitHub issues](https://img.shields.io/github/issues/toqeer788/WebGuard.svg)
![GitHub forks](https://img.shields.io/github/forks/toqeer788/WebGuard.svg)
![GitHub stars](https://img.shields.io/github/stars/toqeer788/WebGuard.svg)
![GitHub license](https://img.shields.io/github/license/toqeer788/WebGuard.svg)

---

## 🚀 Overview

**WebGuard** is an automated multi-tool web vulnerability scanner designed to simplify and streamline web application security testing.

It combines multiple security tools and custom checks into a single workflow, helping security analysts and penetration testers save time while improving efficiency and accuracy.

---

## 🎯 Purpose

Manual vulnerability scanning using multiple tools is time-consuming.

**WebGuard solves this by:**
- Automating multiple scanning tools
- Correlating results from different sources
- Identifying vulnerabilities with better confidence
- Reducing manual effort in security assessments

---

## ✨ Features

- One-step automated scanning
- Integration of multiple security tools
- Custom vulnerability checks
- Classification of vulnerabilities (Critical, High, Medium, Low, Info)
- Cross-tool validation to reduce false positives
- Lightweight and efficient execution
- Structured and readable output
- Scan legends for long-running processes
- Vulnerability descriptions and remediation guidance
- Executive summary of findings

---

## 🔍 Vulnerability Checks

WebGuard performs checks including:

- DNS & WAF detection  
- Subdomain enumeration  
- SSL/TLS vulnerabilities  
- Open ports scanning  
- CMS detection (WordPress, Joomla, Drupal)  
- Directory and file brute-forcing  
- XSS and SQL Injection detection  
- DNS zone transfer checks  
- DoS-related checks (e.g., Slow Loris)  

---

## 🧰 Tools Used

WebGuard integrates multiple security tools such as:

- nmap  
- dnsrecon  
- wafw00f  
- theHarvester  
- amass  
- nikto  
- sslyze / sslscan  
- fierce  
- dnsenum  

*(Make sure these tools are installed on your system, Kali Linux is recommended.)*

---

## ⚙️ Requirements

- Python 3.x  
- Kali Linux (recommended)  
- Ubuntu / Parrot OS (supported)  
- Required external security tools installed  

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/toqeer788/WebGuard.git
cd WebGuard
