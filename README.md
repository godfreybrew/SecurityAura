# Security Aura

A collection of awesome software, libraries, documents, books, resources and cool stuff about security.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python).

Thanks to all [contributors](https://github.com/sbilly/awesome-security/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

- [Awesome Security](#awesome-security)
  - [Network](#network)
    - [Scanning / Pentesting](#scanning--pentesting)
    - [Monitoring / Logging](#monitoring--logging)
    - [IDS / IPS / Host IDS / Host IPS](#ids--ips--host-ids--host-ips)
    - [Honey Pot / Honey Net](#honey-pot--honey-net)
    - [Full Packet Capture / Forensic](#full-packet-capture--forensic)
    - [Sniffer](#sniffer)
    - [Security Information & Event Management](#security-information--event-management)
    - [VPN](#vpn)
    - [Fast Packet Processing](#fast-packet-processing)
    - [Firewall](#firewall)
    - [Anti-Spam](#anti-spam)
    - [Docker](#docker-images-for-penetration-testing--security)
  - [Endpoint](#endpoint)
    - [Anti-Virus / Anti-Malware](#anti-virus--anti-malware)
    - [Content Disarm & Reconstruct](#content-disarm--reconstruct)
    - [Configuration Management](#configuration-management)
    - [Authentication](#authentication)
    - [Mobile / Android / iOS](#mobile--android--ios)
    - [Forensics](#forensics)
  - [Threat Intelligence](#threat-intelligence)
  - [Social Engineering](#social-engineering)
  - [Web](#web)
    - [Organization](#organization)
    - [Web Application Firewall](#web-application-firewall)
    - [Scanning / Pentesting](#scanning--pentesting-1)
    - [Runtime Application Self-Protection](#runtime-application-self-protection)
    - [Development](#development)
  - [Red Team Infrastructure Deployment](#red-team-infrastructure-deployment)
  - [Exploits & Payloads](#exploits--payloads)
  - [Usability](#usability)
  - [Big Data](#big-data)
  - [DevOps](#devops)
  - [Terminal](#terminal)
  - [Operating Systems](#operating-systems)
    - [Online resources](#online-resources)
  - [Datastores](#datastores)
  - [Fraud prevention](#fraud-prevention)
  - [EBooks](#ebooks)
  - [Other Awesome Lists](#other-awesome-lists)
    - [Other Security Awesome Lists](#other-security-awesome-lists)
    - [Other Common Awesome Lists](#other-common-awesome-lists)
  - [Contributing](#contributing)

------

## Network

### Network architecture

- [Network-segmentation-cheat-sheet](https://github.com/sergiomarotco/Network-segmentation-cheat-sheet) - This project was created to publish the best practices for segmentation of the corporate network of any company. In general, the schemes in this project are suitable for any company.

### Scanning / Pentesting

- [OpenVAS](http://www.openvas.org/) - OpenVAS is a framework of several services and tools offering a comprehensive and powerful vulnerability scanning and vulnerability management solution.
- [Metasploit Framework](https://github.com/rapid7/metasploit-framework) - A tool for developing and executing exploit code against a remote target machine. Other important sub-projects include the Opcode Database, shellcode archive and related research.
- [Kali](https://www.kali.org/) - Kali Linux is a Debian-derived Linux distribution designed for digital forensics and penetration testing. Kali Linux is preinstalled with numerous penetration-testing programs, including nmap (a port scanner), Wireshark (a packet analyzer), John the Ripper (a password cracker), and Aircrack-ng (a software suite for penetration-testing wireless LANs).
- [tsurugi](https://tsurugi-linux.org/) - heavily customized Linux distribution that designed to support DFIR investigations, malware analysis and OSINT activities. It is based on Ubuntu 20.04(64-bit with a 5.15.12 custom kernel)
- [pig](https://github.com/rafael-santiago/pig) - A Linux packet crafting tool.
- [scapy](https://github.com/gpotter2/awesome-scapy) - Scapy: the python-based interactive packet manipulation program & library.
- [Pompem](https://github.com/rfunix/Pompem) - Pompem is an open source tool, which is designed to automate the search for exploits in major databases. Developed in Python, has a system of advanced search, thus facilitating the work of pentesters and ethical hackers. In its current version, performs searches in databases: Exploit-db, 1337day, Packetstorm Security...
- [Nmap](https://nmap.org) - Nmap is a free and open source utility for network discovery and security auditing.
- [Amass](https://github.com/caffix/amass) - Amass performs DNS subdomain enumeration by scraping the largest number of disparate data sources, recursive brute forcing, crawling of web archives, permuting and altering names, reverse DNS sweeping and other techniques.
- [Anevicon](https://github.com/rozgo/anevicon) - The most powerful UDP-based load generator, written in Rust.
- [Finshir](https://github.com/isgasho/finshir) - A coroutines-driven Low & Slow traffic generator, written in Rust.
- [Legion](https://github.com/GoVanguard/legion) - Open source semi-automated discovery and reconnaissance network penetration testing framework.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers
- [RustScan](https://github.com/RustScan/RustScan) - Faster Nmap scanning with Rust. Take a 17 minute Nmap scan down to 19 seconds.
- [Boofuzz](https://github.com/jtpereyda/boofuzz) - Fuzzing engine and fuzz testing framework.
- [monsoon](https://github.com/RedTeamPentesting/monsoon) - Very flexible and fast interactive HTTP enumeration/fuzzing.
- [Netz](https://github.com/spectralops/netz)- Discover internet-wide misconfigurations, using zgrab2 and others.
- [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper) - Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless.
- [Deepfence SecretScanner](https://github.com/deepfence/SecretScanner) - Find secrets and passwords in container images and file systems.
- [Cognito Scanner](https://github.com/padok-team/cognito-scanner) - CLI tool to pentest Cognito AWS instance. It implements three attacks: unwanted account creation, account oracle and identity pool escalation