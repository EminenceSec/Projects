# Network Research | Remote Control Project

An automated network reconnaissance tool for remote Linux machines that maintains full anonymity. The tool establishes SSH connections, gathers essential network information, and performs common reconnaissance tasks such as Nmap scans, Whois lookups, and cURL checks.

All traffic is routed through **Nipe** over the **Tor network**, ensuring the script consistently masks the originating IP address throughout the entire process. This automation streamlines network research while minimizing manual effort and maintaining operational discretion.

## Key Features

- **Automated SSH Connections** – Seamlessly connect to remote Linux machines.  
- **Network Scanning** – Perform Nmap scans to map the network and identify open ports.  
- **Domain & Server Info** – Retrieve Whois information and perform cURL checks.  
- **Full Anonymization** – All actions are routed through Nipe/Tor, masking the source IP.  
- **Streamlined Workflow** – Automates repetitive reconnaissance tasks for efficiency and reliability.

## Tools Automatically Installed and Used

The project leverages the following tools to perform its tasks:

- **Bash Scripting** – Automates command execution, manages file paths, and handles report generation.  
- **Nipe** – A Tor-based anonymity tool that forces all system traffic through the Tor network.  
- **Tor** – Provides anonymized communication via distributed relay nodes.  
- **cURL** – Retrieves HTTP response data, such as external IP information, from web servers.  
- **GeoIPLookup** – Determines the geographical location (country) of an IP address.  
- **CPANMinus** – Lightweight, script-friendly tool for installing Perl modules required by Nipe and other utilities.  
- **SSH** – Establishes secure remote connections to Linux machines for research tasks.  
- **SCP** – Securely transfers collected files between machines over SSH.  
- **Nmap** – Performs network scans to identify open ports, running services, and system fingerprints.  
- **Whois** – Retrieves domain registration and ownership information.  
- **Uptime** – Displays how long the system has been running since its last reboot.

## Use Cases

- Ethical hacking and penetration testing  
- Cybersecurity research and red-team exercises  
- Anonymous network reconnaissance

## How to Use

```bash
./Remote_Control.sh
```

## Disclaimer

This tool is intended for **educational and ethical purposes only**. Unauthorized access to systems is illegal and strictly prohibited.
