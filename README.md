<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:00d4ff&height=220&section=header&text=Bhargav%20Baranda&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=SOC%20Analyst%20%7C%20Detection%20Engineer%20%7C%20Security%20Researcher&descSize=18&descAlignY=58&descColor=00d4ff" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=Building+SOC+capabilities+in+public.;MITRE+ATT%26CK+%7C+Splunk+%7C+Sigma+%7C+KQL;10+labs+documented.+89+videos+published.;MSc+Information+Security+%E2%80%94+Royal+Holloway.;Academic+Centre+of+Excellence+in+Cyber+Security+Research.;Every+commit+is+a+rep.)](https://git.io/typing-svg)

<br/>

[![ISC²](https://img.shields.io/badge/ISC²-Certified_in_Cybersecurity-00599C?style=for-the-badge&logoColor=white)](https://www.isc2.org/certifications/cc)
[![Security+](https://img.shields.io/badge/CompTIA-Security+_Certified-EE3124?style=for-the-badge)](https://www.comptia.org/certifications/security)
[![Royal Holloway](https://img.shields.io/badge/Royal_Holloway-MSc_Information_Security-003087?style=for-the-badge)](https://www.royalholloway.ac.uk)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhargav-baranda)
[![YouTube](https://img.shields.io/badge/YouTube-Granger_Security-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![Portfolio](https://img.shields.io/badge/Portfolio-Security_Operations-2D9CDB?style=flat-square&logo=github&logoColor=white)](https://github.com/Granger0007/Bhargav-Baranda-Portfolio)
[![OZONE Shield](https://img.shields.io/badge/Product-OZONE_Shield_🛡️-00d4ff?style=flat-square)](https://ozone-shield.bbaranda055.workers.dev)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bbaranda055@gmail.com)

</div>

---

## About Me

```yaml
name:         Bhargav Baranda
alias:        Granger
location:     Egham, United Kingdom
education:    MSc Information Security — Royal Holloway, University of London (2025)
              Academic Centre of Excellence in Cyber Security Research (NCSC/GCHQ)
credentials:  [ ISC² Certified in Cybersecurity, CompTIA Security+ (SY0-701, certified Aug 2026) ]

background:
  - Behavioural analysis and fraud detection — TTEC, Fraud Prevention & Detection Representative
  - Account takeover, payment fraud, and identity fraud pattern recognition
  - High-volume alert triage across financial services environments (Airbnb, eBay platforms)

current_focus:
  - SOC operations — alert triage, threat hunting, detection engineering
  - Splunk SPL + Microsoft Sentinel KQL + Sigma rule development
  - MITRE ATT&CK at sub-technique level across all investigations
  - ARM64 home lab — purpose-built, fully documented, publicly available

philosophy:   "I don't study security from the outside.
               I build labs, break things, document everything,
               and publish the evidence. Every commit is a rep."

seeking:      SOC Analyst roles across the UK market
available:    Immediately
```

> I completed my MSc at Royal Holloway — one of only a handful of universities in the UK formally recognised as an Academic Centre of Excellence in Cyber Security Research by NCSC and GCHQ. That connection between academic knowledge and national security practice isn't theoretical there. It's built into the institution. It shaped how I think about this field.

---

## SOC Lab Programme — 10 Labs Complete

> Every lab produces a **Detection Triad** (Sigma + SPL + KQL), a full incident report, a GitHub writeup, and a pre-built STAR interview answer. Nothing in isolation.

| # | Lab | Tools | MITRE ATT&CK | Status |
|:-:|---|---|---|:---:|
| 001 | OSI Model & Phishing Analysis | Wireshark, tcpdump | T1566.001 Spearphishing | ✅ |
| 002 | Wireshark TCP Handshake Capture | Wireshark 4.6.x, curl | T1040 Network Sniffing | ✅ |
| 003 | Subnetting Without a Calculator | ipcalc, mental arithmetic | Network architecture | ✅ |
| 004 | DNS Enumeration with dig | dig, nslookup, Team Cymru ASN | T1590.002 DNS · T1498.002 | ✅ |
| 005 | HTTP/HTTPS & TLS Handshake | Wireshark, curl | T1040 · T1557.002 AiTM | ✅ |
| 006 | Ports & Protocols — Top 20 Cold | Knowledge-based reference | T1046 Network Scanning | ✅ |
| 007 | Firewalls, ACLs & DMZ Architecture | iptables, network diagrams | T1190 Exploit Public App | ✅ |
| 008 | Nmap Port Scanning | Nmap 7.99, Wireshark | T1046 Network Discovery | ✅ |
| 009 | Wireshark Deep Dive — Full PCAP Analysis | tshark 4.6.x, Wireshark | T1040 · T1557 · T1071 | ✅ |
| 010 | Log Analysis Fundamentals | syslog, auth.log, Event Viewer | T1078 · T1110 | ✅ |

**Full lab writeups:** [View the complete programme](https://github.com/Granger0007/Bhargav-Baranda-Portfolio)

---

## MITRE ATT&CK Coverage

```
Reconnaissance   ████████░░  T1590 · T1046 · T1498
Initial Access   ████░░░░░░  T1566.001 · T1190
Execution        ██░░░░░░░░  T1204
Defence Evasion  ████░░░░░░  T1036 · T1071
Credential Acc.  ████░░░░░░  T1110 · T1040 · T1557
Discovery        ██████░░░░  T1046 · T1590 · T1018
C2               ████░░░░░░  T1071.001 · T1071.004
Exfiltration     ██░░░░░░░░  T1041 · T1048
```

Coverage expands with every lab. Full technique list in the portfolio repo.

---

## Home Lab

> Enterprise SOC tools assume x86_64. My machine is Apple Silicon ARM64.
> Every workaround is documented and published — reproducible by any analyst on Apple Silicon.

```
MacBook Pro — Apple Silicon M-series (ARM64)
└── UTM Virtualisation
    └── Kali Linux ARM64
        ├── SIEM            →  Splunk (Docker/containerised)  +  ELK Stack 8.x
        ├── IDS / EDR       →  Suricata 7.x  +  Wazuh 4.x
        ├── Network         →  Wireshark 4.6.x · tcpdump · Nmap 7.99
        ├── Forensics       →  Volatility 3 · tshark · NetworkMiner
        ├── Detection Eng   →  Sigma · SPL · KQL
        ├── Offensive       →  Burp Suite · apktool · jadx · ADB
        └── Infrastructure  →  Docker containers — £0 cloud spend
```

---

## What I Build

Everything I work on is documented and published. No private repos, no course certificates without proof of work.

| | Repository | What's Inside | Status |
|:-:|---|---|:---:|
| 🔐 | [Security Operations Portfolio](https://github.com/Granger0007/Bhargav-Baranda-Portfolio) | 10 labs · Incident investigations · Detection rules (Sigma / SPL / KQL) · ARM64 lab documentation | 🟢 Active |
| 📺 | [Granger Security — YouTube](https://github.com/Granger0007/granger-security-youtube) | CVE research · Video scripts · Threat intelligence writeups | 🟢 Active |
| 🛡️ | [OZONE Shield](https://github.com/Granger0007/ozone-shield) | Live AI scam detector — paste any message, get an instant verdict · Claude AI · Cloudflare Workers · Production secured | 🔴 Live |

---

## OZONE Shield — Live Product

> Over 3.4 billion phishing messages are sent every day. Most people have no fast, simple way to check if a message is genuine.

OZONE Shield solves this: paste any suspicious email, SMS, WhatsApp, or letter and receive an instant AI-powered verdict — **SAFE**, **SUSPICIOUS**, or **SCAM** — with a confidence score, specific reasons tied to the actual message, and a plain-English action guide.

No account. No download. Works on any device.

[![Try OZONE Shield](https://img.shields.io/badge/▶_Try_It_Now-ozone--shield.bbaranda055.workers.dev-00d4ff?style=for-the-badge)](https://ozone-shield.bbaranda055.workers.dev)

**Under the hood:** Claude AI (via Cloudflare AI Gateway) · Cloudflare Workers · KV-persistent rate limiting · CORS · CSP headers · API key isolation · Input sanitisation · Production-grade from day one.

---

## Technical Skills

| Domain | Tools & Techniques |
|---|---|
| **SIEM Operations** | Splunk SPL — search, stats, eval, rex, timechart · Microsoft Sentinel KQL · ELK Stack 8.x · Log correlation |
| **Detection Engineering** | Sigma rules · Splunk SPL · KQL · False positive tuning · Alert fatigue reduction · Evasion gap analysis |
| **Network Analysis** | Wireshark · tshark · tcpdump · Suricata IDS · TCP/IP · DNS enumeration · Packet forensics |
| **Threat Intelligence** | MITRE ATT&CK (sub-technique) · CISA KEV · NCSC advisories · IOC enrichment (VirusTotal, OTX, AbuseIPDB) |
| **Incident Response** | NIST SP 800-61 lifecycle · Timeline reconstruction · Root cause analysis · GDPR Article 33 / ICO 72hr |
| **Offensive Tools** | Nmap · Burp Suite · apktool · jadx · ADB · OWASP Top 10 / Mobile Top 10 |
| **Frameworks** | MITRE ATT&CK · NIST CSF · Cyber Kill Chain · PICERL · ISO 27001 |
| **Scripting** | Python · Bash · SPL · KQL · Sigma |

---

## Granger Security — YouTube

89 videos. CVE breakdowns, threat intelligence briefs, SOC lab walkthroughs, and Security+ content — made for aspiring analysts and career changers breaking into the industry.

[![Watch](https://img.shields.io/badge/▶_Watch-Granger_Security_(89_videos)-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)

| Pillar | Content |
|---|---|
| 🔴 CVE Analysis | Breaking vulnerabilities — CVSS, affected versions, patch status, detection rules |
| 🟡 Threat Intel Briefs | Cybersecurity news framed for the SOC analyst |
| 🔵 Lab Walkthroughs | Real detections, real tool output, real mistakes — no polish |
| ⚪ Security+ Explained | Exam concepts anchored to real SOC scenarios |

---

## 2026 Roadmap

```
2025
 ├── ✅  MSc Information Security — Royal Holloway, University of London
 └── ✅  ISC² Certified in Cybersecurity (CC)

Q1–Q2 2026
 ├── ✅  SOC Lab Programme — Labs 001–010 complete
 ├── ✅  OZONE Shield — live AI scam detector (ozone-shield.bbaranda055.workers.dev)
 └── 🔄  UK SOC Analyst job applications          ← active

Q3 2026
 ├── ✅  CompTIA Security+ SY0-701 — passed, first attempt
 ├── 🔄  SOC Analyst role — UK market              ← active
 └── 🎯  Splunk Core Certified User

Q4 2026
 ├── 🎯  Splunk Power User
 ├── 🎯  BTL1 / eJPT
 └── 🎯  Open-source Sigma contributions

2027
 ├── 🎯  CompTIA CySA+
 ├── 🎯  Cloud Security — AZ-500 / AWS Security Specialty
 └── 🎯  Detection Engineering specialism
```

---

## GitHub Stats

<div align="center">

![Granger's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Granger0007&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=ffffff&icon_color=00d4ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Granger0007&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=ffffff)

![GitHub Streak](https://streak-stats.demolab.com?user=Granger0007&theme=tokyonight&hide_border=true&background=0d1117&ring=00d4ff&fire=00d4ff&currStreakLabel=00d4ff)

</div>

---

## Let's Connect

<div align="center">

Actively seeking SOC Analyst roles across the UK market.
If you're hiring, collaborating, or want to talk threat detection — reach out.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhargav-baranda)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![OZONE Shield](https://img.shields.io/badge/Product-OZONE_Shield-00d4ff?style=for-the-badge)](https://ozone-shield.bbaranda055.workers.dev)
[![Email](https://img.shields.io/badge/Email-Get_In_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bbaranda055@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:1a1f2e,100:0d1117&height=120&section=footer"/>

</div>
