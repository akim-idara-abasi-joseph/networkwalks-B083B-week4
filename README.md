# 🛡️ Mediroza General Hospital Penetration Testing Project

## Overview

This repository contains my **Week 4 Cybersecurity Internship** project completed during the **NETWORKWALKS Batch 83** internship program.

The project involved performing a penetration test in an **authorized lab environment**, following a structured methodology from reconnaissance to vulnerability assessment, data analysis, and reporting.

---

## Objectives

- Perform reconnaissance on the target.
- Identify web application vulnerabilities.
- Assess the security of protected PDF documents.
- Analyze exposed metadata and backup files.
- Document findings and recommend appropriate remediation.

---

## Tools Used

- Kali Linux
- curl
- qpdf
- exiftool
- Browser Developer Tools
- Password Cracker
- Hash Calculator

---

## Project Tasks

- Conducted reconnaissance using the `robots.txt` file.
- Identified username enumeration on the login page.
- Tested for SQL injection and demonstrated authentication bypass.
- Retrieved protected PDF reports.
- Extracted PDF hashes and assessed password strength.
- Recovered weak passwords using multiple wordlists.
- Decrypted encrypted PDF files using **qpdf**.
- Examined PDF metadata using **exiftool**.
- Investigated an exposed backup directory.
- Analyzed a database backup.
- Documented vulnerabilities, assessed their impact, and provided remediation recommendations.

---

## Key Learning Outcomes

This project demonstrated how multiple vulnerabilities can be chained together to create a complete attack path. It reinforced the importance of:

- Secure authentication mechanisms
- Preventing SQL injection
- Strong password policies
- Proper file protection
- Metadata security
- Protecting backup files from public access
- Comprehensive vulnerability reporting

---

## Disclaimer

> This project was completed in an **authorized cybersecurity training environment** provided by **NETWORKWALKS**. All activities were performed with explicit permission and strictly for educational purposes.
