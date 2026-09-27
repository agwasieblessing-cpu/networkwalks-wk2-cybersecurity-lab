## NetworkWalks Week 2 – Footprinting & Network Scanning Lab

## Project Overview

This project documents my Week 2 hands-on cybersecurity lab work covering 
Footprinting and reconnaissance with multiple Kali Linux tools, and 
Network scanning with Zenmap.

The main objective was to gather public information about a target domain 
Using passive reconnaissance tools, and to discover live hosts on my own 
Local network using Zenmap, then document the findings in a full 
Penetration testing report.

## Tools Used

- Kali Linux
- Oracle VirtualBox
- WHOIS
- WhatWeb
- Nslookup
- Curl
- Wafw00f
- DNSRecon
- Zenmap (Nmap GUI)
- Windows CMD

## Lab Configuration

- Target domain: networkwalks.com
- Local network: NAT Network
- Kali Linux IP Address: 10.0.0.2/24
- LAN Subnet: 10.0.0.0/24

## Completed

1. Ran WHOIS to find domain registration details for networkwalks.com.
2. Ran WhatWeb to fingerprint web technologies (WordPress, WP Download 
   Manager, Apache).
3. Ran Nslookup to resolve the domain to its IP address.
4. Ran Curl -I to read HTTP response headers.
5. Ran Wafw00f to detect the Web Application Firewall (ModSecurity).
6. Ran DNSRecon to enumerate DNS records (NS, MX, SPF, TXT).
7. Identified my local IP address and LAN subnet.
8. Used Zenmap to run a Ping Scan and discover live hosts on my subnet.
9. Recorded the IP and MAC addresses of all live hosts found.
10. Exported the network topology as a PDF using Zenmap.
11. Documented all findings in a full penetration testing report.

## Scanning Command

The command below was used to discover live hosts on the local subnet:

Nmap -sn 10.0.0.2/24

The scan completed successfully and identified 3 live hosts on the 
Network, confirming active devices reachable from my machine.

## What I Learned

Through this exercise, I gained practical experience with:

-	Using footprinting tools to gather public information about a domain 
  Without directly touching the target.
- Fingerprinting web technologies and identifying exposed information.
- Detecting Web Application Firewalls protecting a website.
- Enumerating DNS records to understand a domain’s infrastructure.
- Using Zenmap to discover live hosts on a local network.
- Reading and interpreting IP addresses, MAC addresses, and network 
  Topology diagrams.
-	Writing a structured cybersecurity report covering findings, risk 
  Levels, and recommendations.

## Evidence

This repository contains screenshots of each tool’s output, the exported 
Network topology PDF, and the full written report documenting the 
Completed lab work.

## Conclusion

The Week 2 lab was successfully completed. Footprinting was performed 
Against networkwalks.com using six Kali Linux tools, and network scanning 
Was performed on my own local subnet using Zenmap. All findings were 
Documented in a full penetration testing report, completed under 
Authorized scope.


