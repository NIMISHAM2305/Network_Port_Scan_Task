# Network_Port_Scan_Task

# Task 1: Scan Your Local Network for Open Ports

## 🔍 Objective
Discover open ports on devices in the local network to understand network exposure and learn basic network reconnaissance.

## 🛠 Tools Used
- Nmap
- Wireshark (Optional)

## 📝 Steps Performed
1. Installed Nmap from the official site.
2. Identified the local IP range using `ipconfig` / `ifconfig`.
3. Ran a TCP SYN scan using: nmap -sS 192.168.56.1/24
4. Analyzed open ports and noted down IP addresses.
5. Interpreted the results and checked for common services.
6. Used Wireshark to observe network packets using the filter : tcp.flags.syn == 1 && tcp.flags.ack == 0
7. Saved the scan results and attached them to this repository.

## 📁 Files Included
- `scan-results.txt` – Output from Nmap scan
- `open ports.png` – Output from Nmap scan on cmd
- `wireshark tcp packets.png`- packets captured by wireshark
- `Documentation.txt`- Explaining the step by step tasks performed


## 📚 Key Concepts
- Port Scanning
- TCP SYN Scan
- IP Addressing
- Network Reconnaissance
- Open Port Security Risks

## ✅ Outcome
Understood how to perform port scans and identify potential vulnerabilities in a local network setup.



