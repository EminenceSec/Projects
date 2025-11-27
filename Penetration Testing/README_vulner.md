# Penetration Testing | VULNER Project

This project automates the process of network scanning, vulnerability assessment, and password strength evaluation. It scans a specified network for active hosts, identifies exposed services, and tests for weak or easily guessable passwords using automated brute‑force techniques.

The script evaluates known vulnerabilities and performs credential testing against **SSH, Telnet, FTP, and RDP**. Users can choose between two operational modes:  

- **Basic Scan** – Identifies active hosts, exposed services, and weak passwords.  
- **Full Scan** – Includes everything in the Basic Scan plus vulnerability mapping via SearchSploit and the Nmap Vulners script.

All collected findings are compiled into a single report for efficient analysis, enabling security analysts and penetration testers to quickly assess the security posture of a network.

## Key Features

- **Automated Network Scanning** – Detect active hosts and exposed services across a target network.  
- **Credential Testing** – Check for weak passwords across SSH, Telnet, FTP, and RDP.  
- **Vulnerability Mapping** – Leverage SearchSploit and Nmap Vulners for deeper security assessment.  
- **Two Scan Modes** – Choose between Basic and Full scanning based on your assessment needs.  
- **Comprehensive Reporting** – Automatically generates a structured, easy‑to‑review report.

## Tools Automatically Installed and Used

The project installs and utilizes the following tools:

- **Bash Scripting** – Handles automation logic, command execution, file management, and report creation.  
- **Nmap** – Detects active hosts, identifies open ports, and extracts service versions for assessment.  
- **Masscan (UDP Port Scanning)** – Performs high‑speed scanning to discover open UDP ports at scale.  
- **SearchSploit** – Searches Exploit‑DB for known exploits tied to discovered services.  
- **Nmap NSE (Vulners Script)** – Matches scan results with known vulnerabilities in multiple databases.  
- **Nmap NSE (Weak Password Brute Force)** – Performs automated brute‑force attempts to identify weak or default credentials for SSH, Telnet, FTP, and RDP.

## Use Cases

- **Penetration Testing & Red Teaming**  
  Automate early‑stage reconnaissance, vulnerability discovery, and password strength evaluation.

- **Network Security Audits**  
  Quickly identify weak credentials, exposed services, and known vulnerabilities in internal networks.

- **IT Security Hygiene Assessments**  
  Validate password policies, check for misconfigurations, and uncover outdated or vulnerable services.

- **Training & Labs**  
  Great for cybersecurity students and researchers learning how to perform network scanning and vulnerability analysis.

## How to Use

```bash
./vulner.sh
```

## Disclaimer

This tool is intended for **educational and ethical purposes only**. Unauthorized access to systems is illegal and strictly prohibited.
