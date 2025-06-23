Port Scanning Task – Cybersecurity Internship - Task 1

Tools Used
- Nmap (SYN scan, version detection)
- Kali Linux Live

Objective
Identify open ports in the local network `192.168.84.0/24` to analyze exposed services.

Commands Used
bash
nmap -sS -sV 192.168.84.0/24 -oN scan.txt

