# Linux Server Hardening Script

This repository contains a Bash script designed to **harden** a Linux server by applying a series of security best practices.  
The goal is to improve the system's security posture, minimize vulnerabilities, and prepare it for production environments.

---

## 🛠️ Features

- Full system update and upgrade
- Install and configure **Fail2Ban** for basic intrusion prevention
- Configure **iptables** firewall rules
- Disable ICMP (ping) responses
- Enable strict **kernel hardening** sysctl parameters
- Install and configure **apt-listbugs** and **apt-listchanges**
- Secure SSH configurations:
  - Disable root login
  - Disable password authentication
  - Restrict SSH to a specific port (`4000`)
  - Limit login attempts
- Set strict file permissions on critical system files
- Install and run **Lynis** for security auditing

---

## 📋 How to Use

Clone this repository:

   ```bash
   git clone https://github.com/yourusername/linux-server-hardening.git
   cd linux-server-hardening

