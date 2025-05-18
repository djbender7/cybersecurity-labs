# 🧠 Cybersecurity Labs — Offensive Security Playground

This repository documents my hands-on cybersecurity projects conducted in an isolated lab environment. Using VirtualBox, Kali Linux, and Metasploitable 2, I’ve explored real-world vulnerabilities, post-exploitation techniques, and privilege escalation methods.

---

## ⚙️ Lab Environment

| Component       | Details                            |
|----------------|-------------------------------------|
| Hypervisor      | VirtualBox (Host-Only Network)     |
| Attacker VM     | Kali Linux (192.168.56.101)        |
| Victim VM       | Metasploitable 2 (192.168.56.102)  |

> All machines are isolated from the internet to ensure safe experimentation.

---

## 🔓 Exploits Completed

| Exploit Name                          | Technique           | Privilege | Report Link |
|--------------------------------------|---------------------|-----------|-------------|
| UnrealIRCd 3.2.8.1 Backdoor (CVE-2010-2075) | Remote Code Execution (RCE) | root      | [View Report](./metasploitable/unreal_ircd/unreal_ircd_exploit.md) |
| Nmap SUID Binary Exploit             | Privilege Escalation | root      | [View Notes](./metasploitable/nmap_suid/notes.md) |

---

## 📁 Directory Structure

CYBERSECURITY-LABS/
├── metasploitable/
│ ├── custom-scripts/
│ │ └── reverse_shells/
│ ├── nmap_suid/
│ │ ├── notes.md
│ │ └── root_shell.png
│ ├── unreal_ircd/
│ │ ├── screenshots/
│ │ ├── notes.md
│ │ └── unreal_ircd_exploit.md
│ └── vsftpd/
├── README.md

---

## 📌 Upcoming Projects

- [ ] Password Cracker (John/Hashcat)
- [ ] DNS Spoofing via Ettercap
- [ ] Keylogger in Python
- [ ] Honeypot (Cowrie or HoneyDB)
- [ ] Threat Detection w/ ML (Zeek + Python)
- [ ] Rootkits & Kernel Backdoors (Advanced)
- [ ] Full Disk Encryption Experiment
- [ ] Custom Python Assessment Tool

---

## 🔒 Disclaimer

All activities are performed in a **legally isolated and controlled environment**.  
These labs are intended for educational and ethical hacking purposes only.

---

