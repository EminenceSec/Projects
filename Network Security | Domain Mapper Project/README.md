# Network Security | Domain Mapper Project

An automated network security testing tool designed to simplify Active Directory and Domain Controller penetration testing. The tool guides users through a streamlined setup process, requesting a network range and credentials before launching into fully automated security assessments.

The project offers three operational modes — **Scanning**, **Enumeration**, and **Exploitation** — each with adjustable intensity levels: **Basic**, **Intermediate**, **Advanced**, or **None**. By automating tasks such as service discovery, vulnerability assessment, and brute‑forcing, the tool significantly reduces manual work and accelerates domain mapping, enumeration, and exploitation activities.

## Key Features

- **Automated AD/DC Assessment** – Simplifies domain‑level scanning and reconnaissance.  
- **Flexible Operational Modes** – Choose between Scanning, Enumeration, and Exploitation.  
- **Intensity Control** – Adjust the depth of analysis with Basic, Intermediate, or Advanced levels.  
- **Streamlined Workflow** – Automates complex security tasks for faster and more accurate results.

## Tools Automatically Installed and Used

The project automatically installs and leverages the following tools:

- **Bash Scripting** – Manages automation logic, command execution, and report generation.  
- **Nmap** – Scans networks, identifies hosts, and detects service versions for vulnerability assessment.  
- **Masscan (UDP Port Scanning)** – Rapidly discovers open UDP ports across large network ranges.  
- **Nmap NSE** – Enables advanced vulnerability detection, detailed enumeration, and network discovery.  
- **smbclient** – Interacts with SMB shares for file access, enumeration, and permission testing.  
- **rpcclient** – Queries Windows systems over SMB for users, shares, groups, and permissions.  
- **enum4linux** – Extracts users, shares, groups, and password policies from Windows hosts.  
- **CrackMapExec** – Automates enumeration and exploitation across SMB, RDP, WinRM, and other Windows protocols.  
- **Hashcat** – Performs brute‑force, dictionary, and rule‑based attacks to crack hashed passwords.  
- **Enscript** – Converts text reports into formats like PostScript, HTML, or RTF for clean report output.  
- **Ghostscript** – Processes and converts PostScript/PDF files within reporting workflows.  
- **Python3** – Powers additional automation, parsing, and custom tooling used throughout the project.

## Use Cases

- **Penetration Testing of Active Directory Environments**  
  Quickly assess the security posture of Windows domains, including services, shares, and users.

- **Red Team Infrastructure Mapping**  
  Automate the process of mapping, enumerating, and identifying exploitation paths across Windows networks.

- **Credential and Access Evaluation**  
  Use brute‑forcing and credential testing capabilities to analyze account strength and identify weak points.

- **Network Security Research & Training**  
  Great for learning or demonstrating the workflow of domain reconnaissance and exploitation in lab environments.

## How to Use

1. Download the project ZIP file.  
2. Extract all files into a directory of your choice.  
3. Open a terminal inside the extracted folder.  
4. Run the main script:

```bash
./Domain_Mapper.sh
```

## Disclaimer

This tool is intended for **educational and ethical purposes only**. Unauthorized access to systems is illegal and strictly prohibited.
