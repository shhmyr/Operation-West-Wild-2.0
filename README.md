# Operation West Wild 2.0 – Penetration Testing Report

## 📌 Overview

This repository contains a full penetration testing assessment conducted in a controlled lab environment. The project demonstrates a complete attack lifecycle from reconnaissance to full system compromise.

## 🎯 Objectives

* Identify vulnerabilities in the target system
* Exploit misconfigurations
* Achieve privilege escalation
* Capture system flags

## 🧪 Lab Environment

* Attacker Machine: Kali Linux
* Target Machine: West Wild OVA
* Network: Isolated Lab (Bridged)

## 🛠 Tools Used

* Nmap – Network scanning
* Netdiscover – Host discovery
* Dirb – Directory enumeration
* Burp Suite – Web application testing
* Metasploit – Exploitation
* LinEnum – Privilege escalation

## 🔍 Methodology

1. Reconnaissance
2. Initial Access
3. Enumeration
4. Privilege Escalation
5. Flag Discovery

## 🔑 Key Findings

* Exposure of sensitive directories and files
* Weak authentication mechanisms
* Vulnerable CMS plugin leading to remote code execution
* Privilege escalation via PATH hijacking


## 📄 Report

[Download Full Report](./Report/westwild-report.pdf)

## ⚠️ Disclaimer

This project was conducted in a controlled lab environment for educational purposes only. Do not attempt these techniques on systems without proper authorization.
