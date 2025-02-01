
# Python Hacking Tools

## Overview
This repository contains a collection of Python-based hacking tools designed for penetration testing and ethical hacking. The tools included in this project are:

- **Port Scanner** – Scan open ports on a target system.
- **SSH Brute Force** – Attempt to gain unauthorized access via SSH brute-force attack.
- **ARP Poisoning** – Perform a Man-in-the-Middle (MITM) attack by spoofing ARP tables.

> **Disclaimer:** These tools are intended for educational and ethical hacking purposes only. Unauthorized use on systems without explicit permission is illegal and punishable by law.

## Features
- Simple and modular Python scripts.
- Uses popular libraries such as `scapy`, `paramiko`, and `socket`.
- Supports logging and verbose output for debugging.
- Cross-platform support (Linux, Windows, MacOS).

## Installation
Ensure you have Python 3 installed on your system. Then, clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/python-hacking-tools.git
cd python-hacking-tools
pip install -r requirements.txt
```

## Tools Usage
### 1. Port Scanner
Scans for open ports on a specified target.
```bash
python port_scanner.py -t <target_ip> -p <port_range>
```
Example:
```bash
python port_scanner.py -t 192.168.1.1 -p 1-1000
```

### 2. SSH Brute Force
Attempts to brute-force SSH login credentials.
```bash
python ssh_brute.py -t <target_ip> -u <username> -w <wordlist>
```
Example:
```bash
python ssh_brute.py -t 192.168.1.1 -u admin -w passwords.txt
```

### 3. ARP Poisoning
Performs an ARP spoofing attack between two targets.
```bash
python arp_poison.py -t <target_ip> -g <gateway_ip>
```
Example:
```bash
python arp_poison.py -t 192.168.1.100 -g 192.168.1.1
```

## Dependencies
Ensure the following Python libraries are installed:
```bash
pip install scapy paramiko socket
```

## Legal Disclaimer
This project is for educational purposes only. Any misuse of these tools is solely the user's responsibility. Always obtain permission before testing on any network or system.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
**Author:** [Your Name]  
**GitHub:** [Your GitHub Profile]
