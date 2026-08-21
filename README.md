🛡️ Cybersecurity Roadmap v3: Advanced Pentesting, Red Teaming & Security Research

A practical roadmap and modern toolkit for progressing from beginner to Penetration Tester → Red Teamer → Exploit Developer → Security Researcher.

⚠️ Ethical & Legal Use: Use security tools only against systems you own or have explicit authorization to test. Safe environments include home labs, CTFs, Hack The Box, TryHackMe, PortSwigger Web Security Academy, and explicitly authorized bug bounty programs.

🚀 1. OSINT & Reconnaissance
🔎 Search & Intelligence
Shodan
Censys
Google Dorking
Bing Search Operators
crt.sh
SecurityTrails
DNSDumpster
Have I Been Pwned
👤 Username / Email Enumeration
Sherlock
Maigret
theHarvester
Holehe
WhatsMyName
🌐 Domain & Attack-Surface Discovery
Amass
Subfinder
Sublist3r
Assetfinder
Recon-ng
Maltego
SpiderFoot
dnsx
puredns
MassDNS
⚡ Modern Recon Pipeline
Subfinder
    ↓
DNSx
    ↓
HTTPx
    ↓
Naabu
    ↓
Katana
    ↓
Nuclei
    ↓
Burp Suite

🌐 2. Network & Infrastructure Pentesting
🔍 Scanning
Nmap
Masscan
Naabu
RustScan
Unicornscan
🛡️ Vulnerability Assessment
Nessus
OpenVAS / Greenbone
Nuclei
Nexpose / InsightVM
📡 Traffic Analysis
Wireshark
tcpdump
tshark
Zeek
🔧 Network Utilities
Netcat
Socat
Proxychains
Responder
Bettercap
mitmproxy
💥 Exploitation
Metasploit Framework
SearchSploit
Exploit-DB
Core Impact
🕸️ 3. Web Application Security
🔥 Web Proxies
Burp Suite
OWASP ZAP
mitmproxy
🗂️ Content Discovery
ffuf
Gobuster
Feroxbuster
Dirsearch
Dirb
💉 Injection Testing
SQLmap
NoSQLMap
Commix
tplmap
🔐 Authentication & Session Security
JWT Tool
Autorize
Burp extensions
OAuth testing tools
🧩 CMS Security
WPScan
Droopescan
JoomScan
📚 Must-Know Vulnerability Classes
SQL Injection
XSS
SSRF
CSRF
XXE
SSTI
IDOR / BOLA
Path Traversal
Command Injection
File Upload vulnerabilities
Prototype Pollution
Request Smuggling
Web Cache Poisoning
Deserialization
Authentication flaws
Access-Control flaws
🔌 4. API Security

Modern applications are heavily API-driven, so API pentesting deserves its own track.

🛠️ Tools
Burp Suite
Postman
Insomnia
Kiterunner
Arjun
ffuf
HTTPie
InQL
🔷 GraphQL
InQL
GraphQL Voyager
Burp Suite GraphQL extensions
🔑 API Technologies to Learn
REST
GraphQL
gRPC
WebSockets
OAuth 2.0
OpenID Connect
JWT
API Keys
🎯 Common API Issues
BOLA / IDOR
Broken authentication
Excessive data exposure
Mass assignment
Rate-limit weaknesses
Privilege escalation
Improper authorization
🏢 5. Active Directory & Windows Pentesting

One of the most important tracks for professional pentesters and red teamers.

🧠 Enumeration
BloodHound / BloodHound CE
NetExec
PowerView
LDAP tools
AdFind
🔐 Kerberos
Rubeus
Impacket
Kerbrute
🪪 AD CS
Certipy
🖥️ Remote Administration / Windows Testing
Evil-WinRM
Impacket
NetExec
📦 Impacket

Important modules include:

secretsdump
GetUserSPNs
GetNPUsers
psexec
wmiexec
smbexec
📚 Learn
LDAP
Kerberos
NTLM
SMB
Group Policy
Windows authentication
Trust relationships
AD CS
Delegation
ACLs
Privilege escalation
☁️ 6. Cloud Security
AWS
Tools
Prowler
ScoutSuite
CloudFox
Pacu
Enumerate-IAM
TruffleHog
Learn
IAM
S3
EC2
Lambda
Security Groups
CloudTrail
STS
Roles
Trust Policies
Azure / Entra ID
Tools
BloodHound
ROADtools
AzureHound
Microsoft Graph tooling
Learn
Entra ID
OAuth
Managed Identities
Service Principals
Conditional Access
Azure RBAC
GCP

Learn:

IAM
Service Accounts
GCS
Compute Engine
Workload Identity
Organization Policies
🐳 7. Containers & Kubernetes
🐋 Container Security
Trivy
Grype
Syft
Docker Scout
Hadolint
☸️ Kubernetes
kube-bench
kube-hunter
Peirates
Kubescape
Falco
🏗️ Infrastructure as Code
Checkov
tfsec
KICS
📚 Learn
Docker
Kubernetes
RBAC
Secrets
Service Accounts
Network Policies
Container isolation
Kubernetes admission controls
🔓 8. Passwords & Credential Security
Offline Password Auditing
Hashcat
John the Ripper
Ophcrack
Authentication Testing
Hydra
Medusa
NetExec
Kerbrute
Credential Discovery
Gitleaks
TruffleHog
detect-secrets
Credential Digger
📚 Learn
NTLM
Kerberos
bcrypt
scrypt
Argon2
PBKDF2
Password spraying
Credential reuse
Credential stuffing
Secrets management
📡 9. Wireless Security
📶 Wi-Fi
Aircrack-ng
Kismet
Wifite
hcxdumptool
hcxpcapngtool
🌐 Network
Bettercap
Wireshark
tcpdump
📚 Learn
WPA2
WPA3
802.11
EAP
Rogue AP concepts
Wireless authentication
Network segmentation
📱 10. Mobile Security
Android
MobSF
jadx
apktool
Frida
Objection
adb
Drozer
iOS
Frida
Objection
MobSF
LLDB
class-dump
📚 Learn
Android internals
APK structure
Android permissions
IPC
Deep links
Secure storage
Certificate pinning
Mobile API security
🧬 11. Reverse Engineering
🔬 Disassemblers / Decompilers
Ghidra
IDA Pro / IDA Free
Binary Ninja
Cutter
radare2
Rizin
🐛 Debuggers
GDB
pwndbg
GEF
x64dbg
WinDbg
LLDB
📚 Learn
Assembly
x86/x64
ARM
ELF
PE
Calling conventions
Memory layout
Stack / heap
Dynamic linking
Windows internals
Linux internals
💥 12. Binary Exploitation

For exploit development and vulnerability research.

🛠️ Tools
pwntools
pwndbg
GEF
GDB
ROPgadget
Ropper
angr
Z3
📚 Learn
Buffer overflows
Stack smashing
ASLR
DEP / NX
PIE
RELRO
Stack canaries
ROP
ret2libc
Format strings
Heap exploitation
Use-after-free
Integer overflows
🧪 13. Fuzzing
🔥 Fuzzing Frameworks
AFL++
libFuzzer
honggfuzz
Boofuzz
Peach
Jazzer
🌐 Web / Protocol Fuzzing
ffuf
Burp Intruder
Wfuzz
Boofuzz
📚 Learn
Coverage-guided fuzzing
Mutation-based fuzzing
Grammar-based fuzzing
Crash triage
Sanitizers
Corpus management
Code coverage
🦠 14. Malware Analysis
🐧 Linux
REMnux
🪟 Windows
FLARE-VM
🔬 Analysis
Ghidra
x64dbg
WinDbg
Detect It Easy
Procmon
Process Explorer
Autoruns
🧬 Malware Detection
YARA
CAPA
FLOSS
📚 Learn
Static analysis
Dynamic analysis
PE format
Persistence
Command & Control concepts
Obfuscation
Packers
Behavioral analysis
🕵️ 15. Digital Forensics & DFIR
💾 Forensics
Autopsy
The Sleuth Kit
KAPE
Plaso
Timesketch
🧠 Memory Forensics
Volatility 3
🖥️ Endpoint Investigation
Velociraptor
osquery
📚 Learn
Windows Event Logs
Registry
Prefetch
Amcache
Shimcache
Browser artifacts
Memory analysis
Timeline analysis
🛡️ 16. Blue Team & Detection Engineering

A strong red teamer should understand how defenders detect attacks.

SIEM / Security Monitoring
Wazuh
Elastic Security
Splunk
Microsoft Sentinel
Network Detection
Zeek
Suricata
Endpoint
Sysmon
osquery
Velociraptor
Detection Rules
Sigma
YARA
Suricata rules
📚 Learn
MITRE ATT&CK
Detection engineering
Threat hunting
Log analysis
Incident response
EDR telemetry
SIEM correlation
🤖 17. Automation & Security Programming
Languages
Python — automation, tooling, APIs, security research
Bash — Linux automation
PowerShell — Windows/AD
Go — networking and security tooling
JavaScript — web security
C/C++ — exploit development and low-level research
SQL — databases and injection research
Python Libraries
Requests
Scapy
pwntools
Impacket
Paramiko
BeautifulSoup
aiohttp
Goal

Don't just learn to run tools.

Learn to modify them, automate them, combine them, and eventually write your own.

🧠 18. Security Research
Research Areas
CVE analysis
Vulnerability discovery
Patch diffing
Reverse engineering
Fuzzing
Protocol analysis
Browser security
Kernel security
Cryptography
Hardware security
Resources / Databases
CVE
NVD
Exploit-DB
GitHub Security Advisories
Packet Storm
MITRE ATT&CK
OWASP
🏴‍☠️ 19. Red Teaming
Core Concepts
Initial Access
Execution
Persistence
Privilege Escalation
Defense Evasion
Credential Access
Discovery
Lateral Movement
Collection
Command & Control
Exfiltration
Impact

Study these through MITRE ATT&CK and controlled labs rather than treating them as a collection of attack commands.

Frameworks / Platforms
Metasploit
Sliver
Mythic
Havoc
Covenant

Use C2 frameworks only in environments where you have explicit authorization.

🔐 20. DevSecOps / Application Security
SAST
Semgrep
CodeQL
SonarQube
SCA
Dependabot
Grype
Trivy
Secrets
Gitleaks
TruffleHog
IaC
Checkov
KICS
tfsec
CI/CD Security

Learn to audit:

GitHub Actions
GitLab CI
Jenkins
Docker
Kubernetes
Terraform
Secrets management
🧰 21. Essential Security Distributions
🐉 Kali Linux

General-purpose pentesting environment.

🐧 Parrot Security

Pentesting + privacy-focused environment.

🦅 BlackArch

Arch-based security environment for advanced users.

🔬 REMnux

Malware analysis.

🪟 FLARE-VM

Windows reverse engineering and malware research.

🧪 Security Onion

Network security monitoring and defensive research.

🎯 22. Practice Platforms
Beginner → Intermediate
TryHackMe
Hack The Box
PortSwigger Web Security Academy
Advanced
HTB Academy
PentesterLab
PortSwigger labs
VulnHub
OverTheWire
CTF / Research
pwn.college
picoCTF
Root-Me
CryptoHack
Bug Bounty
HackerOne
Bugcrowd
Intigriti

Always follow the target's explicit scope and rules.

📚 23. Knowledge You MUST Have

Tools are secondary. The foundation is:

Networking
TCP/IP
UDP
DNS
HTTP/HTTPS
TLS
SMTP
FTP
SSH
SMB
LDAP
Kerberos
Operating Systems
Linux internals
Windows internals
Processes
Threads
Memory
Filesystems
Permissions
Services
Web
HTTP
Cookies
Sessions
CORS
CSP
OAuth
JWT
REST
GraphQL
WebSockets
Programming
Python
Bash
PowerShell
JavaScript
C
SQL
🗺️ 24. Recommended Learning Path
                    ┌─────────────────┐
                    │ Computer Basics │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │ Linux + Windows │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │ Networking      │
                    │ TCP/IP + DNS    │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │ Python + Bash   │
                    │ PowerShell      │
                    └────────┬────────┘
                             ↓
              ┌──────────────┴──────────────┐
              ↓                             ↓
        Web Pentesting                Network Pentesting
              ↓                             ↓
        API Security                 Active Directory
              ↓                             ↓
              └──────────────┬──────────────┘
                             ↓
                    ┌─────────────────┐
                    │ Cloud + Docker  │
                    │ + Kubernetes    │
                    └────────┬────────┘
                             ↓
                ┌────────────┴────────────┐
                ↓                         ↓
          Red Teaming              Reverse Engineering
                ↓                         ↓
                │                  Exploit Development
                │                         ↓
                └────────────┬────────────┘
                             ↓
                    Security Research

🏆 25. Final Skill Progression
🟢 Beginner
Linux
Networking
Python
Bash
HTTP
Nmap
Wireshark
Burp Suite
🔵 Junior Pentester
Web vulnerabilities
API testing
Enumeration
Privilege escalation
Metasploit
Active Directory basics
Reporting
🟣 Pentester
Advanced web
API security
AD
Cloud
Containers
Vulnerability assessment
Custom scripting
🔴 Red Teamer
AD attack paths
Windows internals
C2 concepts
OPSEC
Detection evasion concepts
MITRE ATT&CK
Detection engineering
⚫ Exploit Developer
C/C++
Assembly
GDB
Ghidra
pwntools
Fuzzing
Memory corruption
ROP
Heap internals
🧬 Security Researcher
Reverse engineering
Fuzzing
Vulnerability discovery
CVE analysis
Patch diffing
Binary analysis
Kernel/browser research
Custom tooling
🧰 The Ultimate Toolkit
RECON
├── Amass
├── Subfinder
├── Shodan
├── Censys
├── dnsx
├── httpx
├── Naabu
└── Nuclei

WEB / API
├── Burp Suite
├── OWASP ZAP
├── ffuf
├── Katana
├── Kiterunner
├── SQLmap
├── Arjun
└── JWT Tool

NETWORK
├── Nmap
├── Wireshark
├── tcpdump
├── Netcat
├── Masscan
└── Zeek

ACTIVE DIRECTORY
├── BloodHound
├── NetExec
├── Impacket
├── Rubeus
├── Certipy
├── Kerbrute
└── Evil-WinRM

CLOUD
├── Prowler
├── ScoutSuite
├── CloudFox
├── Pacu
└── ROADtools

CONTAINERS
├── Trivy
├── Grype
├── Syft
├── Checkov
└── Falco

MOBILE
├── MobSF
├── Frida
├── Objection
├── jadx
├── apktool
└── adb

REVERSE ENGINEERING
├── Ghidra
├── IDA
├── Binary Ninja
├── x64dbg
├── GDB
├── pwndbg
└── radare2

EXPLOIT DEVELOPMENT
├── pwntools
├── ROPgadget
├── Ropper
├── angr
└── Z3

FUZZING
├── AFL++
├── libFuzzer
├── honggfuzz
└── Boofuzz

MALWARE RESEARCH
├── REMnux
├── FLARE-VM
├── YARA
├── CAPA
├── FLOSS
└── x64dbg

DFIR
├── Volatility 3
├── Autopsy
├── KAPE
├── Velociraptor
└── Timesketch

BLUE TEAM
├── Wazuh
├── Suricata
├── Zeek
├── Sigma
├── Sysmon
└── Elastic Security


Author: m2xdev
Version: 3.0 — Advanced Pentesting, Red Teaming & Security Research