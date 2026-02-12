# Task-1-Scan-Your-Local-Network-for-Open-Ports

NMAP COMMANDS:

1.nmap -sn 192.168.1.0/24
Scans Entire subnet for hosts.

2. nmap 192.168.1.10
Scan top 1000 TCP ports
 
3. nmap -sV 192.168.1.10
Detects running services and versions.

4. nmap -p- 192.168.1.10  
Scans all 65535 TCP ports
 
5. nmap -O 192.168.1.10
Detects OS details
 
6. nmap -A 192.168.1.10
Aggressive Scan – OS detection, Service detection, Script Scanning and Traceroute
 
7. nmap -sU 192.168.1.10
UDP port scan.
 
8. nmap 192.168.1.1-50
Scans multiple targets (Works like angry IP scanner)

The ouput for the above commands has been attached in the repo as a word file.
