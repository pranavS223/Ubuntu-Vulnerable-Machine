# Vulnerable Machine for Cybersecurity Education

![Difficulty](https://img.shields.io/badge/Difficulty-Easy%2FMedium-green)
![Platform](https://img.shields.io/badge/Platform-Linux-blue)
![Category](https://img.shields.io/badge/Category-Web%2C%20PrivEsc-red)

A vulnerable Ubuntu machine featuring PHP misconfiguration and LaTeX injection vulnerabilities for cybersecurity training.

## 🚀 Quick Info

- **OS**: Ubuntu 16.04 LTS
- **Difficulty**: Easy/Medium
- **Author**: [Your Name]

## 📋 Machine Description

This machine is a research-focused Ubuntu machine with a LaTeX-to-PDF conversion web application. The machine demonstrates real-world misconfigurations in PHP handling and cron job vulnerabilities.

## 🔍 Vulnerabilities

### Phase 1: Initial Access
- **PHP Handler Misconfiguration** - Double extension bypass (.phar.ltx)
- **File Upload Vulnerability** - Weak file validation

### Phase 2: Privilege Escalation  
- **Sudo Misconfiguration** - PATH hijacking via system_audit binary
- **Cron Job Injection** - LaTeX --shell-escape command execution

## 🛠️ Installation

1. Download `machine.ova.zip` from the Machine folder
2. Extract password: `[password]`
3. Import into VirtualBox/VMware
4. Start the machine

## 🎯 Learning Objectives

- PHP configuration security
- Sudo misconfigurations
- Cron job vulnerabilities
- LaTeX command injection
- Defense against double extension attacks

## ⚠️ Legal Disclaimer

This machine is created for educational purposes only. Use only in controlled environments with proper authorization.
