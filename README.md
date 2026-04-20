# 🐧 Linux Server Security Project – NovaTech Solutions

## 📌 Overview

I deployed and secured a Linux server to simulate a real-world enterprise environment.

This project focuses on system administration, access control, and security hardening techniques used in production systems.

---

## 🎯 Objectives

* Deploy a Linux server in a virtual environment
* Implement user and group management
* Configure file permissions and ownership
* Secure remote access (SSH hardening)
* Implement firewall rules
* Protect against brute-force attacks using fail2ban
* Monitor and analyze system logs

---

## 🏢 Scenario

NovaTech Solutions required a secure Linux server to manage internal services and users.

I was responsible for configuring and securing the server to meet enterprise security standards.

---

## 🛠️ Technologies Used

* Ubuntu Server
* UTM (Virtualization)
* SSH (Secure Remote Access)
* UFW (Firewall)
* fail2ban (Intrusion Prevention)

---

## ⚙️ System Setup

### Server Configuration

* 4 GB RAM
* 4 CPU cores
* 20 GB storage

### Installation

Ubuntu Server was installed in a virtual machine using UTM, with OpenSSH enabled for remote management.

---

## 👥 User & Group Management

I created users and groups to simulate departments:

* HR
* Finance
* IT

This allows role-based access control within the system.

---

## 🔐 File Permissions

I configured file permissions to restrict access to sensitive data:

* Used `chmod` to control access
* Used `chown` to assign ownership

This ensures only authorized users can access specific resources.

---

## 🔒 SSH Hardening

To secure remote access, I:

* Disabled root login
* Changed default SSH port
* Restarted SSH service

This reduces exposure to brute-force attacks.

---

## 🔥 Firewall Configuration (UFW)

I configured firewall rules to allow only required services:

* Allowed SSH on custom port
* Blocked all unnecessary traffic

---

## 🚫 Intrusion Prevention (fail2ban)

I installed and configured fail2ban to:

* Monitor login attempts
* Automatically block malicious IPs

This protects against brute-force attacks.

---

## 📊 Log Analysis

I analyzed system logs to monitor activity:

* Login attempts
* System events
* Errors

This is essential for detecting suspicious behavior.

---

## 🧪 Testing & Validation

* Verified user access restrictions
* Confirmed firewall rules are active
* Tested SSH security configuration
* Observed logs for system activity

---

## 📸 Key Screenshots

### Server Installation

![Installation](Screenshots/install.png)

### User Management

![Users](Screenshots/users.png)

### File Permissions

![Permissions](Screenshots/permissions.png)

### SSH Configuration

![SSH](Screenshots/ssh.png)

### Firewall (UFW)

![Firewall](Screenshots/ufw.png)

### Fail2Ban

![Fail2Ban](Screenshots/fail2ban.png)

### Logs

![Logs](Screenshots/logs.png)

---

## 🚧 Challenges & Solutions

* SSH misconfiguration caused connection issues → fixed by verifying config file
* Incorrect file permissions blocked access → corrected ownership and permissions
* Firewall initially blocked SSH → adjusted rules to allow correct port

---

## 📈 Key Takeaways

* Gained hands-on experience in Linux system administration
* Learned practical security hardening techniques
* Improved troubleshooting and log analysis skills
* Understood real-world server management workflows

---

## 🧠 Conclusion

This project demonstrates my ability to deploy, secure, and manage a Linux server in a real-world scenario.

It reflects practical skills required for roles such as:

* Junior Linux Administrator
* System Administrator
* Cybersecurity Analyst

---
