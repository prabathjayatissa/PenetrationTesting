# Penetration Testing Study Guide for Bachelor’s Students

---

# Year 1 — Foundations

## What is Penetration Testing?

Penetration testing (or “pentesting”) is the legal and authorized process of testing computer systems, networks, and applications to find security weaknesses before attackers do.

A penetration tester acts like an ethical hacker:
- Finds vulnerabilities
- Exploits them safely
- Reports how to fix them

---

# 1. Skills You Need to Learn First

## A. Computer Networking

Learn:
- IP addresses
- DNS
- Routers & switches
- TCP vs UDP
- Ports and protocols
- HTTP/HTTPS
- VPNs
- Firewalls

### Important protocols

| Protocol | Port | Purpose |
|---|---|---|
| HTTP | 80 | Web traffic |
| HTTPS | 443 | Secure web |
| SSH | 22 | Remote login |
| FTP | 21 | File transfer |
| DNS | 53 | Domain resolution |

---

## B. Linux Fundamentals

Most security work happens on Linux.

Learn:
- File system navigation
- Permissions
- Bash commands
- Package management
- Processes/services
- Networking commands

### Essential commands

```bash
ls
cd
pwd
chmod
grep
find
curl
wget
netstat
ss
```

### Recommended distributions
- Kali Linux
- Parrot OS

---

## C. Programming Basics

Focus on:
- Python
- Bash scripting
- Basic JavaScript
- SQL basics

Programming helps automate:
- Reconnaissance
- Scanning
- Exploitation
- Reporting

---

# 2. Core Cybersecurity Concepts

## CIA Triad

| Principle | Meaning |
|---|---|
| Confidentiality | Prevent unauthorized access |
| Integrity | Prevent unauthorized changes |
| Availability | Keep systems accessible |

---

## Common Vulnerabilities

Learn:
- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection
- Broken Authentication
- File Inclusion
- Buffer Overflow
- Weak Passwords

---

# 3. Penetration Testing Process

## Phase 1 — Reconnaissance

Gather information about the target.

### Tools
- Nmap
- theHarvester

---

## Phase 2 — Scanning & Enumeration

Find:
- Open ports
- Running services
- Versions
- Vulnerabilities

### Example

```bash
nmap -sV 192.168.1.10
```

---

## Phase 3 — Exploitation

Use vulnerabilities to gain access.

### Tools
- Metasploit Framework
- Burp Suite

---

## Phase 4 — Post Exploitation

Learn:
- Privilege escalation
- Persistence
- Credential collection
- Lateral movement

---

## Phase 5 — Reporting

A professional report should include:
- Executive summary
- Vulnerabilities found
- Risk levels
- Screenshots
- Remediation steps

---

# 4. Best Platforms for Students

## Beginner-Friendly Labs

- TryHackMe
- Hack The Box
- OverTheWire

---

# 5. Recommended Learning Path (First Year)

## Months 1–2

Learn:
- Networking
- Linux basics
- Command line
- Python basics

---

## Months 3–4

Learn:
- Web technologies
- HTTP/HTTPS
- HTML basics
- JavaScript basics
- SQL basics

Practice:
- OWASP Juice Shop
- DVWA labs

---

## Months 5–6

Learn:
- Nmap
- Burp Suite
- Wireshark
- Basic exploitation

---

## Months 7–12

Focus on:
- Web pentesting
- Linux privilege escalation
- Capture The Flag (CTF)
- Report writing

---

# 6. Ethical and Legal Rules

Never:
- Attack systems without permission
- Scan public systems aggressively
- Steal credentials/data
- Use tools maliciously

Ethical hacking requires:
- Written authorization
- Defined scope
- Responsible disclosure

---

# 7. Certifications to Aim For Later

## Beginner
- CompTIA Security+
- eJPT

## Intermediate
- PNPT
- OSCP

---

# 8. Recommended Books

- The Web Application Hacker's Handbook
- Linux Basics for Hackers
- Black Hat Python

---

# 9. Suggested Home Lab Setup

Use:
- VirtualBox or VMware
- Kali Linux VM
- Vulnerable targets

### Vulnerable machines
- Metasploitable
- OWASP Juice Shop
- DVWA

---

# 10. Final Advice for Year 1

1. Focus on fundamentals first
2. Practice daily
3. Learn Linux deeply
4. Build projects
5. Document everything
6. Stay ethical and legal

---

---

# Year 2 — Intermediate Penetration Testing

---

# 1. Advanced Networking & Infrastructure

Learn:
- Subnetting
- VLANs
- Routing
- NAT
- DNS internals
- DHCP
- Active Directory basics

Topics:
- Packet crafting
- Traffic analysis
- Network segmentation
- IDS/IPS systems

### Tools
- Wireshark
- tcpdump
- Netcat

---

# 2. Operating System Internals

## Linux Internals

Study:
- Kernel basics
- Process management
- System calls
- Memory management
- Permissions and ACLs
- PAM authentication

---

## Windows Internals

Learn:
- Windows Registry
- Services
- DLLs
- LSASS
- PowerShell
- Active Directory

---

# 3. Web Application Penetration Testing

Master:
- Sessions
- Cookies
- Authentication
- JWT tokens
- CSRF protections
- CORS
- APIs

### Vulnerabilities
- SQL Injection
- NoSQL Injection
- Command Injection
- LDAP Injection
- XSS
- SSRF
- XXE
- IDOR
- Race conditions
- Deserialization

---

# 4. Scripting & Automation

Learn Python topics:
- Requests library
- Socket programming
- Multithreading
- Regex
- API interaction
- Parsing data

### Projects
- Port scanners
- Directory brute forcers
- Log analyzers
- Vulnerability scanners

---

# 5. Active Directory Security

Learn:
- Domains
- Forests
- Kerberos
- LDAP
- Group Policy
- SMB
- NTLM

### Attack concepts
- Pass-the-Hash
- Kerberoasting
- Lateral movement
- Delegation abuse
- BloodHound analysis

### Tools
- BloodHound
- Mimikatz

---

# 6. Wireless Security

Learn:
- Wi-Fi protocols
- WPA2/WPA3
- Handshake capture
- Rogue AP concepts
- Evil Twin attacks

### Tools
- Aircrack-ng

---

# 7. Reverse Engineering Basics

Learn:
- Assembly basics
- x86 architecture
- PE and ELF files
- Debugging basics

### Tools
- Ghidra
- x64dbg

---

# 8. Vulnerability Research Basics

Study:
- CVEs
- CVSS scoring
- Exploit databases
- Patch diffing

---

# 9. Cloud Security Fundamentals

Learn basics of:
- AWS
- Microsoft Azure
- Google Cloud

Understand:
- IAM
- Cloud networking
- Security groups
- Containers

---

# 10. Containers & DevOps Security

Learn:
- Docker
- Kubernetes basics
- CI/CD pipelines
- Secrets management

---

# 11. Intermediate Home Lab

Include:
- Kali VM
- Windows Server
- Active Directory
- Vulnerable Linux machines
- SIEM/logging tools

### Suggested additions
- Security Onion
- Splunk Free
- pfSense firewall

---

# 12. Realistic Practice Platforms

Continue:
- TryHackMe
- Hack The Box

Add:
- VulnHub

---

# 13. Soft Skills Matter

Develop:
- Report writing
- Communication
- Presentation skills
- Time management
- Client professionalism

Write:
- Technical blogs
- Lab reports
- CTF writeups

---

# 14. Suggested Second-Year Projects

## Beginner Projects
- Python port scanner
- Password strength checker
- Vulnerable web app deployment

## Intermediate Projects
- Mini SIEM
- Web fuzzer
- Phishing awareness simulator
- Local AD lab

---

# 15. Certifications for Second Year

Good targets:
- eJPT
- PNPT
- Security+
- Linux+

### Advanced path
- Begin OSCP preparation

---

# 16. Suggested Study Timeline

## Semester 1

Focus:
- Web security
- Burp Suite
- Python automation
- Linux internals

---

## Semester 2

Focus:
- Active Directory
- Windows privilege escalation
- Cloud basics
- Reverse engineering basics

---

# 17. Career Paths to Explore

| Area | Focus |
|---|---|
| Web Pentesting | Web applications & APIs |
| Red Teaming | Adversary simulation |
| Malware Analysis | Reverse engineering |
| Cloud Security | AWS/Azure/GCP |
| SOC/Blue Team | Detection & response |
| DevSecOps | Secure CI/CD |
| Bug Bounty | Public vulnerability hunting |

---

# 18. End-of-Year Goal

By the end of second year, aim to:
- Complete medium HTB machines
- Understand Active Directory attacks
- Write professional reports
- Automate tasks with Python
- Understand web application vulnerabilities deeply
- Build a multi-VM security lab
- Participate in CTF competitions confidently
