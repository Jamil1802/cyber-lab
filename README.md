# cyber-lab
Educational lab with Kali Linux, Metasploitable, and pfSense for ethical hacking practice.

# 🛡️ Educational Cybersecurity Lab

This repository documents my **educational lab** built with **Kali Linux, Metasploitable, and pfSense**.  
The goal is to practice ethical hacking, penetration testing, and network defense in a safe, controlled environment.

---

## 📦 Requirements
- **Hardware**: Minimum 8GB RAM, 100GB free disk space
- **Software**:
  - VirtualBox or VMware Workstation
  - Kali Linux (attacker machine)
  - Metasploitable (vulnerable target)
  - pfSense (firewall/IDS)
  - Optional: Windows 10/11 VM for realistic targets

---

## ⚙️ Lab Setup
1. Install virtualization software (VirtualBox/VMware).
2. Create VMs:
   - **Kali Linux** → attacker
   - **Metasploitable** → vulnerable target
   - **pfSense** → firewall/router
3. Configure networking:
   - Use **Host-Only** or **NAT** mode for isolation.
   - Ensure all VMs can communicate internally but are blocked from external internet.
4. Install tools:
   - Kali: Nmap, Wireshark, Metasploit, Burp Suite
   - pfSense: firewall rules, IDS/IPS

---

## 🎯 Practice Projects
- **Port Scanning**: Map services with Nmap.
- **Exploitation**: Test vulnerabilities on Metasploitable.
- **Traffic Analysis**: Capture and inspect packets with Wireshark.
- **Firewall Rules**: Configure pfSense and attempt bypass.
- **Documentation**: Write reports for each exercise.

---

## ⚠️ Legal Disclaimer
This lab is **for educational purposes only**.  
Do not use these techniques on systems you do not own or without explicit permission.

---

## 📚 Learning Goals
- Understand how attacks are performed and defended.
- Gain hands-on experience with penetration testing tools.
- Build a portfolio of cybersecurity projects.
- Prepare for certifications (CEH, OSCP, CompTIA Security+).

---

## 🤝 Contributions
Suggestions and improvements are welcome.  
This repository is part of my journey in cybersecurity and networking.
