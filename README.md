# Project 01 — Network Reconnaissance & Port Scanning Using Nmap

<p align="center">
  <strong>Penetration Testing Project Series</strong><br/>
  Basic Level | Kali Linux | Nmap
</p>

## 📌 Project Overview

This project focuses on understanding the fundamentals of network reconnaissance and port scanning using Nmap on Kali Linux.

The primary objective is to identify network information, discover open ports, detect running services, and understand how network scanning contributes to security assessments.

This project is part of my hands-on Penetration Testing Project Series, progressing from Basic to Intermediate and Advanced levels.

## 🎯 Objectives

- Understand network reconnaissance fundamentals.
- Identify local IP addresses and network interfaces.
- Perform TCP port scanning.
- Detect running services and their versions.
- Explore operating system detection.
- Understand open, closed, and filtered ports.
- Analyze and document scan results.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Penetration Testing Environment |
| Nmap | Network Scanning |
| Linux Terminal | Command Execution |
| Networking Tools | Network Information Gathering |

## 🔍 Practical Tasks

### 1. System Information

```bash
ip addr
ip route
```

### 2. Basic Port Scanning

```bash
nmap 127.0.0.1
```

### 3. Service Version Detection

```bash
nmap -sV 127.0.0.1
```

### 4. Operating System Detection

```bash
sudo nmap -O 127.0.0.1
```

### 5. Full TCP Port Scanning

```bash
nmap -p- 127.0.0.1
```

### 6. Saving Scan Results

```bash
sudo nmap -sV -O -p- 127.0.0.1 -oN detailed-scan.txt
```

## 📂 Project Structure

```text
Project-01/
│
├── README.md
├── screenshots/
│   ├── network-information.png
│   ├── basic-scan.png
│   ├── service-detection.png
│   └── detailed-scan.png
│
├── scan-results/
│   └── detailed-scan.txt
│
└── report/
    └── penetration-testing-report.md
```

## 📚 Learning Outcomes

- Understanding network reconnaissance.
- Practical experience with Nmap.
- Identifying open network ports.
- Understanding service enumeration.
- Analyzing network scan results.
- Documenting security assessment activities.

## 🔐 Ethical Considerations

All scanning activities are performed against localhost or authorized systems.

This project is intended strictly for educational purposes and ethical cybersecurity learning.

## 👨‍💻 Author

**Hamza Riaz**

Cybersecurity Learner | Penetration Testing Enthusiast

## 📈 Project Series

- [x] Project 01 — Network Reconnaissance & Port Scanning (Initial Setup and Scanning)
- [ ] Project 02 — Port Scanning & Service Enumeration
- [ ] Project 03 — Web Server Information Gathering
- [ ] Project 04 — Basic Vulnerability Scanning
- [ ] Project 05 — Password Security Auditing

---

⭐ If you find this project useful, feel free to explore the repository and follow my cybersecurity learning journey.
