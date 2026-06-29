->Port-Scanning-TCP-SYN-scan.
discover open ports on devices in your local network and understand network exposure.

Environment
- macOS Sequoia
- Apple M4 MacBook Air
- Nmap 7.99

Command Used:
sudo nmap -sS 192.168.1.0/24 -oN syn_scan.txt
