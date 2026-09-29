<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:00d4ff&height=220&section=header&text=Bhargav%20Baranda&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Security%2B%20%C2%B7%20ISC%C2%B2%20CC%20%C2%B7%20MSc%20Information%20Security&descSize=18&descAlignY=58&descColor=00d4ff" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=Building+SOC+skills+in+public.;Wazuh+%7C+Elastic+%7C+Splunk+%7C+Sigma;10+labs+documented.+230%2B+videos+%26+Shorts+published.;MSc+Information+Security+%E2%80%94+Royal+Holloway.;Every+commit+is+a+rep.)](https://git.io/typing-svg)

<br/>

[![ISC²](https://img.shields.io/badge/ISC²-Certified_in_Cybersecurity-00599C?style=for-the-badge&logoColor=white)](https://www.isc2.org/certifications/cc)
[![Security+](https://img.shields.io/badge/CompTIA-Security+_Certified-EE3124?style=for-the-badge)](https://www.comptia.org/certifications/security)
[![Royal Holloway](https://img.shields.io/badge/Royal_Holloway-MSc_Information_Security-003087?style=for-the-badge)](https://www.royalholloway.ac.uk)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhargav-baranda)
[![YouTube](https://img.shields.io/badge/YouTube-Granger_Security-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![Portfolio](https://img.shields.io/badge/Portfolio-Security_Operations-2D9CDB?style=flat-square&logo=github&logoColor=white)](https://github.com/Granger0007/Bhargav-Baranda-Portfolio)
[![OZONE Shield](https://img.shields.io/badge/Project-OZONE_Shield_🛡️-00d4ff?style=flat-square)](https://ozone-shield.bbaranda055.workers.dev)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bbaranda055@gmail.com)

</div>

---

## About Me

```yaml
name:          Bhargav Baranda
alias:         Granger
location:      Egham, United Kingdom — open to relocating anywhere in the UK
education:     MSc Information Security — Royal Holloway, University of London (2025)
credentials:   [ CompTIA Security+ (SY0-701, Aug 2026), ISC² Certified in Cybersecurity ]

background:
  - Fraud Prevention & Detection Representative — TTEC
  - Behavioural anomaly detection: account takeover, payment fraud, identity fraud
  - High-volume alert triage and incident escalation for global marketplace clients (Airbnb, eBay)
  - Compliance documentation to PCI-DSS, GDPR and SOX

current_focus:
  - Wazuh and Elastic SIEM, built on cloud lab servers
  - Writing detection rules in Sigma, SPL and KQL, mapped to MITRE ATT&CK
  - Turning every lab into a written investigation

philosophy:    "I don't study security from the outside.
                I build labs, break things, document everything,
                and publish the evidence. Every commit is a rep."

seeking:       L1 / L2 SOC Analyst roles in the UK
right_to_work: Full UK right to work
available:     Immediately
```

Royal Holloway's Information Security Group is an NCSC-recognised Academic Centre of Excellence in Cyber Security Research — that's where my MSc comes from.

---

## SOC Lab Programme — 10 Labs Complete

Each lab is written up in the portfolio with its MITRE ATT&CK mapping. Seven of the ten include a detection set: the same logic written as a Sigma rule, a Splunk SPL search and a KQL query.

| # | Lab | Tools | MITRE ATT&CK | Status |
|:-:|---|---|---|:---:|
| 001 | OSI Model & Phishing Analysis | Wireshark, tcpdump | T1566.001 Spearphishing Attachment | ✅ |
| 002 | Wireshark TCP Handshake Capture | Wireshark 4.6.x, curl | T1040 Network Sniffing | ✅ |
| 003 | Subnetting Without a Calculator | ipcalc, mental arithmetic | Network architecture | ✅ |
| 004 | DNS Enumeration with dig | dig, nslookup, Team Cymru ASN | T1590.002 DNS · T1498.002 | ✅ |
| 005 | HTTP/HTTPS & TLS Handshake | Wireshark, curl | T1040 · T1557.002 AiTM | ✅ |
| 006 | Ports & Protocols — Top 20 Cold | Knowledge-based reference | T1046 Network Service Discovery | ✅ |
| 007 | Firewalls, ACLs & DMZ Architecture | iptables, network diagrams | T1190 Exploit Public-Facing Application | ✅ |
| 008 | Nmap Port Scanning | Nmap 7.99, Wireshark | T1046 Network Service Discovery | ✅ |
| 009 | Wireshark Deep Dive — Full PCAP Analysis | tshark 4.6.x, Wireshark | T1040 · T1557 · T1071 | ✅ |
| 010 | Log Analysis Fundamentals | syslog, auth.log, Event Viewer | T1078 · T1110 | ✅ |

**Full lab write-ups:** [View the complete programme](https://github.com/Granger0007/Bhargav-Baranda-Portfolio)

### Current projects

| Project | What it is | Status |
|---|---|:---:|
| **[MYDFIR Wazuh SOC Analyst Challenge](https://github.com/Granger0007/Bhargav-Baranda-Portfolio/tree/main/projects/wazuh-soc-lab)** | Built a Wazuh SIEM on a cloud server with Windows and Linux agents, file integrity monitoring, two custom detections and an automatic SSH block — which caught real attackers from the internet | ✅ Completed Sept 2026 · [read the write-up](https://github.com/Granger0007/Bhargav-Baranda-Portfolio/tree/main/projects/wazuh-soc-lab) |
| **MYDFIR Elastic SOC Challenge** | ELK Stack, Sysmon and Mythic C2 — building, attacking and detecting, one step a day | 🔄 In progress |

---

## MITRE ATT&CK Coverage

Techniques covered across the labs so far, grouped by tactic:

| Tactic | Techniques |
|---|---|
| Reconnaissance | T1590.002 |
| Resource Development | T1584.004 |
| Initial Access | T1566.001 · T1190 · T1078 |
| Execution | T1204.002 · T1059.005 |
| Defence Evasion | T1027 · T1036 |
| Credential Access | T1110 · T1040 · T1557 |
| Discovery | T1046 · T1018 · T1040 |
| Lateral Movement | T1021.002 · T1210 |
| Command and Control | T1071.001 · T1071.004 · T1573.001 |
| Exfiltration | T1041 · T1048 |
| Impact | T1498.002 |

Coverage grows with every lab. The full list, with the procedure observed for each technique, is in the portfolio repo.

---

## Home Lab

> Enterprise SOC tools assume x86_64. My machine is an Apple Silicon Mac (ARM64) with 8 GB of RAM.
> So light work runs locally, and anything SIEM-sized goes on a cloud server. Every workaround is documented, so anyone on Apple Silicon can reproduce it.

```
MacBook Pro — Apple Silicon M-series (ARM64, 8 GB)
└── UTM
    └── Kali Linux ARM64
        ├── Network         →  Wireshark 4.6.x · tshark · tcpdump · Nmap 7.99
        ├── IDS             →  Suricata 7.x
        ├── SIEM (local)    →  Splunk in Docker (x86 emulation)
        ├── Forensics       →  Volatility 3 · NetworkMiner
        ├── Detection Eng   →  Sigma · SPL · KQL
        └── Offensive       →  Burp Suite · apktool · jadx · ADB

Vultr cloud servers — 2 vCPU / 8 GB / London, one per project
├── Wazuh 4.x           →  Wazuh challenge, Sept 2026: server + Ubuntu agent  (deleted after submission)
└── Elastic Stack       →  Elastic challenge: Elasticsearch · Kibana · Sysmon  (in progress)
```

Why the cloud: a full Wazuh or Elastic deployment needs about 8 GB on its own — all the memory the Mac has. So each one gets its own small cloud server, and I delete the server once the project is finished, so I only pay while it's in use.

---

## What I Build

Everything I work on is documented and published. No private repos, no course certificates without proof of work.

| | Repository | What's Inside | Status |
|:-:|---|---|:---:|
| 🔐 | [Security Operations Portfolio](https://github.com/Granger0007/Bhargav-Baranda-Portfolio) | 10 labs · Incident investigations · Detection rules (Sigma / SPL / KQL) · Lab setup guides | 🟢 Active |
| 📺 | [Granger Security — YouTube](https://github.com/Granger0007/granger-security-youtube) | Channel overview and content plan | 🟢 Active |
| 🛡️ | [OZONE Shield](https://github.com/Granger0007/ozone-shield) | Free AI scam checker — paste a message, get a verdict with reasons · Claude API · Cloudflare Workers | 🟢 Live |

---

## OZONE Shield

Most people have no quick way to tell whether a message is genuine. OZONE Shield is a free tool I built for exactly that: paste a suspicious email, text, WhatsApp message or letter and get a verdict — **SAFE**, **SUSPICIOUS** or **SCAM** — with a confidence score, the specific reasons from that message, and plain-English advice on what to do next.

No account. No download. Works on any device.

[![Try OZONE Shield](https://img.shields.io/badge/▶_Try_It_Now-ozone--shield.bbaranda055.workers.dev-00d4ff?style=for-the-badge)](https://ozone-shield.bbaranda055.workers.dev)

**Under the hood:** Claude API (via Cloudflare AI Gateway) · Cloudflare Workers · rate limiting · CORS and CSP headers · API key kept server-side · input sanitisation. Built and deployed solo.

---

## Technical Skills

| Domain | Tools & Techniques |
|---|---|
| **SIEM** | Wazuh (cloud deployment, custom rules) · Elastic / ELK · Splunk SPL — search, stats, eval, rex, timechart · Log correlation |
| **Detection Engineering** | Sigma rules · Splunk SPL · KQL · Wazuh custom rules · MITRE ATT&CK mapping · False-positive tuning |
| **Network Analysis** | Wireshark · tshark · tcpdump · Suricata IDS · TCP/IP · DNS enumeration · Packet analysis |
| **Threat Intelligence** | MITRE ATT&CK (sub-technique) · CISA KEV · NCSC advisories · IOC enrichment (VirusTotal, OTX, AbuseIPDB) |
| **Incident Response** | NIST SP 800-61r3 · Timeline reconstruction · Root cause analysis · GDPR Article 33 / ICO 72-hour reporting |
| **Fraud & Behavioural Analytics** | Account takeover · Payment and identity fraud patterns · High-volume alert triage (TTEC) |
| **Identity** | Microsoft Entra ID — MFA, Conditional Access, role-based access control |
| **Offensive Tools** | Nmap · Burp Suite · apktool · jadx · ADB · OWASP Top 10 / Mobile Top 10 |
| **Frameworks** | MITRE ATT&CK · NIST CSF 2.0 · Cyber Kill Chain · PICERL · ISO 27001 · PCI-DSS |
| **Languages** | Python · Bash · SPL · KQL · Sigma (YAML) |

---

## Granger Security — YouTube

230+ videos and Shorts since 2022. The current focus is short, daily explainers across three series — **AI Security**, **SOC Analyst** and **Learn Python** — alongside an archive of longer CVE breakdowns and Security+ content.

[![Watch](https://img.shields.io/badge/▶_Watch-Granger_Security-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)

| Series | Content |
|---|---|
| 🟢 AI Security Shorts | One concept per Short — from how computers work up to prompt injection and the EU AI Act |
| 🔵 SOC Analyst Shorts | The skills an L1 analyst uses daily — triage, SIEM, logs, ATT&CK, incident response |
| 🟡 Learn Python Shorts | Python from zero, with a security angle |
| 🔴 CVE Analysis (archive) | Vulnerability breakdowns — CVSS, affected versions, patch status, detection opportunity |

---

## Roadmap

```
2025
 ├── ✅  MSc Information Security — Royal Holloway, University of London
 └── ✅  ISC² Certified in Cybersecurity (CC)

Q1–Q2 2026
 ├── ✅  SOC Lab Programme — Labs 001–010
 └── ✅  OZONE Shield — live AI scam checker

Q3 2026
 ├── ✅  CompTIA Security+ SY0-701 — passed first attempt
 ├── ✅  MYDFIR Wazuh SOC Analyst Challenge
 ├── 🔄  MYDFIR Elastic SOC Challenge
 └── 🔄  UK SOC Analyst applications              ← active

Q4 2026
 ├── 🎯  Splunk Core Certified User
 ├── 🎯  Splunk Power User
 ├── 🎯  BTL1 / eJPT
 └── 🎯  Open-source Sigma contributions

2027
 ├── 🎯  CompTIA CySA+
 ├── 🎯  Cloud security — AZ-500 / AWS Security Specialty
 └── 🎯  Detection engineering specialism
```

---

## Let's Connect

<div align="center">

Looking for an L1 / L2 SOC Analyst role anywhere in the UK.
If you're hiring, or want to talk detection and response — get in touch.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhargav-baranda)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![OZONE Shield](https://img.shields.io/badge/Project-OZONE_Shield-00d4ff?style=for-the-badge)](https://ozone-shield.bbaranda055.workers.dev)
[![Email](https://img.shields.io/badge/Email-Get_In_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bbaranda055@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:1a1f2e,100:0d1117&height=120&section=footer"/>

</div>
