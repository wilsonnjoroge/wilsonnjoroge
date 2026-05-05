# Wilson Njoroge Wanderi 

> **From Backend Engineer to Security Professional** — a structured, hands-on journey through the complete attack-and-defense lifecycle.

<p align="center">
    <a href="https://www.linkedin.com/in/wilson-njoroge-wanderi-ccep-cc-kcna-itil%C2%AE4-pho-33b615166/">
        <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    &nbsp;
    <a href="https://github.com/wilsonnjoroge/?tab=follow">
        <img src="https://img.shields.io/github/followers/wilsonnjoroge?label=Follow&style=social" alt="GitHub Followers"/>
    </a>
    &nbsp;
    <a href="mailto:wilsonnjoroge932@gmail.com">
        <img src="https://img.shields.io/badge/Email-Contact-red?style=flat-square&logo=gmail" alt="Email"/>
    </a>
    &nbsp;
    <a href="https://www.isc2.org/Certifications/CC">
        <img src="https://img.shields.io/badge/ISC2-CC-006400?style=flat-square" alt="ISC2 CC"/>
    </a>
    &nbsp;
    <img src="https://komarev.com/ghpvc/?username=wilsonnjoroge&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

---

## About Me

I'm a Cybersecurity & Digital Forensics engineer with 2+ years of experience securing banking and enterprise integration environments at Equity Group Holdings. Hands-on capability in SIEM deployment (Wazuh), network intrusion detection (Suricata), vulnerability assessment, penetration testing, and security incident detection. Proven track record of producing executive-ready security reports, remediation roadmaps, and audit-ready documentation. Holds ISC2 CC certification; advancing toward CompTIA Security+.

Currently pursuing an MSc in Cyber Security & Digital Forensics, I'm working through the complete security lifecycle — not just the offensive side. Every project here is documented end-to-end: from pre-engagement setup and evidence capture through to professional reporting.

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| Certified in Cybersecurity (CC) | ISC2 | ✅ Completed |
| MSc Cyber Security & Digital Forensics | Open University of Kenya | 🔄 In Progress |
| CompTIA Security+ | CompTIA | 🔄 In Progress |

---

## Learning Philosophy

Security expertise built the right way — following the full attack-and-defense lifecycle in sequence:

```
┌─────────────────────────────────────────────────────────────┐
│                    SECURITY LIFECYCLE                       │
├─────────────────────────────────────────────────────────────┤
│  1. IDENTIFY  → What's vulnerable and why?                  │
│     Vulnerability Assessment & Management          ✅ Done  │
│                                                             │
│  2. EXPLOIT   → How are weaknesses actually attacked?       │
│     Controlled Penetration Testing              🔄 Active   │
│                                                             │
│  3. DETECT    → How do we see attacks happening?            │
│     SIEM / SOC & Security Monitoring            🔄 Active   │
│                                                             │
│  4. PREVENT   → How do we stop vulnerabilities at source?   │
│     Application Security & Secure Development   🗓 Planned  │
│                                                             │
│  5. SECURE    → How do we architect secure environments?    │
│     Cloud & Infrastructure Security             🗓 Planned  │
│                                                             │
│  6. RESPOND   → How do we handle security incidents?        │
│     Incident Response & Digital Forensics       🗓 Planned  │
└─────────────────────────────────────────────────────────────┘
```

---

## Projects

---

### Phase 1 — Vulnerability Assessment & Management ✅

> Comprehensive vulnerability assessment of Metasploitable2 using enterprise-grade tools and a structured 7-phase methodology. Each scanner is a standalone repository with full evidence, raw results, screenshots, and a professional technical report.

#### Metasploitable2 — Master Report

| Document | Link |
|---|---|
| Executive Summary | [View Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/reports/metasploitable2-executive-summary-report.md) |
| Full Technical Report | [View Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/reports/metasploitable2-full-technical-report.md) |
| Attack Chain Analysis | [View Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/reports/metasploitable2-attack-chains-analysis.md) |

---

#### Scanner Repositories

<table>
  <tr>
    <th>Tool</th>
    <th>Repository</th>
    <th>What Was Done</th>
    <th>Key Output</th>
  </tr>
  <tr>
    <td>🔍 Nmap</td>
    <td><a href="https://github.com/wilsonnjoroge/Nmap-Metasploitable-Vulnerability-Assessment">Nmap Repo</a></td>
    <td>8 scan types: initial, service/version, full port (-p-), aggressive, UDP top-100, UDP common, vuln scripts, safe scripts</td>
    <td><a href="https://github.com/wilsonnjoroge/Nmap-Metasploitable-Vulnerability-Assessment/blob/main/04-reporting/metasploitable2-full-technical-report.md">Technical Report</a></td>
  </tr>
  <tr>
    <td>🛡 OpenVAS</td>
    <td><a href="https://github.com/wilsonnjoroge/OpenVAS-Metasploitable-Vulnerability-Assessment">OpenVAS Repo</a></td>
    <td>Full GVM/OpenVAS setup from scratch, authenticated scan, PDF + CSV export</td>
    <td><a href="https://github.com/wilsonnjoroge/OpenVAS-Metasploitable-Vulnerability-Assessment/blob/main/04-reporting/metasploitable2-full-technical-report.md">Technical Report</a></td>
  </tr>
  <tr>
    <td>🔎 Nessus</td>
    <td><a href="https://github.com/wilsonnjoroge/Nessus-Metasploitable-Vulnerability-Assessment">Nessus Repo</a></td>
    <td>Nessus Essentials install, basic network scan policy, full results analysis</td>
    <td><a href="https://github.com/wilsonnjoroge/Nessus-Metasploitable-Vulnerability-Assessment/blob/main/04-reporting/metasploitable2-full-technical-report.md">Technical Report</a></td>
  </tr>
  <tr>
    <td>🌐 Nikto</td>
    <td><a href="https://github.com/wilsonnjoroge/Nikto-Metasploitable-Vulnerability-Assessment">Nikto Repo</a></td>
    <td>HTTP default scan, defined-ports scan, SSL scan against web services</td>
    <td><a href="https://github.com/wilsonnjoroge/Nikto-Metasploitable-Vulnerability-Assessment/blob/main/04-reporting/metasploitable2-nikto-report.md">Technical Report</a></td>
  </tr>
  <tr>
    <td>🖥 Manual Enumeration</td>
    <td><a href="https://github.com/wilsonnjoroge/Manual-Enumeration-Metasploitable">Manual Enumeration Repo</a></td>
    <td>13 services manually enumerated: SSH, FTP, Telnet, SMTP, DNS, HTTP, Tomcat, MySQL, PostgreSQL, RPC/NFS, Java RMI, X11, Web</td>
    <td><a href="https://github.com/wilsonnjoroge/Manual-Enumeration-Metasploitable/blob/main/04-reporting/metasploitable2-full-technical-report.md">Technical Report</a></td>
  </tr>
</table>

#### Manual Enumeration — Services Covered

| Service | Port | Techniques Used |
|---|---|---|
| SSH | 22 | Version detection, algorithm enumeration, auth method testing, credential testing |
| FTP | 21 | Banner grab, anonymous login test, version fingerprinting |
| Telnet | 23 | Banner grab, connection test, traffic capture (Wireshark .pcap) |
| SMTP | 25 | Version detection, VRFY user enumeration, open relay test |
| DNS | 53 | dig queries, version script, recursion test |
| HTTP / Web | 80 | dirb, gobuster, technology fingerprinting, curl enumeration |
| Apache Tomcat | 8180 | Service enum, web enum, directory bruteforce, manager interface check |
| MySQL | 3306 | Credential test, full session enumeration |
| PostgreSQL | 5432 | Credential test, full session enumeration |
| RPC / NFS | 111/2049 | Port scan, rpcinfo dump, NFS script verification |
| Java RMI | 1099 | Version detection, registry dump |
| X11 | 6000 | Service detection, access test |
| Banner Analysis | All | Custom bash script across all open ports |

---

### Phase 1 (Bonus) — Digital Forensics: PhotoRec File Recovery

**Repository:** [PhotoRec-Recovery](https://github.com/wilsonnjoroge/PhotoRec-Recovery)

Practical file recovery exercise using PhotoRec on Linux. Covers image selection, file signature configuration, and recovery of deleted files from a disk image.

| Evidence | Description |
|---|---|
| `Photorec-Linux-Image-Selection.png` | Target image selection |
| `Photorec-Linux-File-Signatures-To-Recover.png` | Configured file types |
| `Photorec-Linux-File-Recovery-1.png` | Recovery in progress |
| `Photorec-Linux-File-Recovered-Docs-1.png` | Recovered files |

---

### Phase 2 — Penetration Testing 🔄 In Progress

**Repository:** [penetration-testing](https://github.com/wilsonnjoroge/penetration-testing)

Controlled exploitation of validated vulnerabilities from Phase 1. Targets: Metasploitable2, DVWA, OWASP Juice Shop.

---

### Phase 3 — SIEM & Detection Engineering 🔄 In Progress

> Virtualized SOC environment built on Wazuh SIEM + Suricata IDS. Covers the full detection engineering lifecycle — from deploying a SIEM and configuring log ingestion, to simulating real attacker TTPs and validating alert generation against MITRE ATT&CK. 4 active agents across Linux and Windows targets.

#### SOC Lab — Key Documents

| Document | Link |
|---|---|
| Executive Methodology | [View Doc](https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/siem_methodology_executive.md) |
| Operational Runbook | [View Doc](https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/siem_lab_runbook.md) |
| Setup Guide | [View Doc](https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/setup-guide.md) |

---

#### Tools & Components

<table>
  <tr>
    <th>Tool</th>
    <th>Repository</th>
    <th>What Was Done</th>
    <th>Key Output</th>
  </tr>
  <tr>
    <td>🛡 Wazuh SIEM</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>All-in-one deployment: Manager, Indexer, Dashboard, Filebeat. 4 agents (Kali, Metasploitable3, Windows 11, host Ubuntu). Agent group configs for Linux + Windows log collection</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/setup-guide.md">Setup Guide</a></td>
  </tr>
  <tr>
    <td>🌐 Suricata IDS</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>Network IDS installed on Wazuh VM. eve.json → Wazuh integration. Custom local rules for Hydra, SQLMap, DVWA SQLi. False positive suppression via threshold.conf</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/configs/suricata/local.rules">Local Rules</a></td>
  </tr>
  <tr>
    <td>🔨 Hydra</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>SSH brute force against Metasploitable3 Ubuntu (rockyou.txt). RDP brute force against Windows 11. Validated Wazuh rules 5763 + 60204 (level 10)</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/attack-scenarios/ssh-bruteforce.md">SSH Bruteforce Scenario</a></td>
  </tr>
  <tr>
    <td>🔍 Nmap</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>SYN scan and aggressive scan against all targets. Validated Suricata + Wazuh recon detection (rules 40101, 40111). Custom rule for Nmap HTTP user-agent in web logs</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/attack-scenarios/nmap.md">Nmap Scenario</a></td>
  </tr>
  <tr>
    <td>💣 Metasploit</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>vsftpd 2.3.4 backdoor exploit against Metasploitable3. Validated FTP anomaly detection (rule 5712, level 10). Mapped to T1190 — Exploit Public-Facing Application</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/siem_lab_runbook.md">Runbook Phase 4</a></td>
  </tr>
  <tr>
    <td>🐚 Netcat</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab">siem-detection-lab</a></td>
    <td>Reverse shell simulation between Kali and Metasploitable3. Validated suspicious process + command execution detection (rule 92200, level 10). Mapped to T1059</td>
    <td><a href="https://github.com/wilsonnjoroge/siem-detection-lab/blob/main/docs/siem_lab_runbook.md">Runbook Phase 4</a></td>
  </tr>
</table>

#### Attack Phases — Coverage Breakdown

| Phase | Tests Run | Targets | MITRE Techniques |
|---|---|---|---|
| **Phase 1 — Visibility** | Agent connectivity, SSH failed login, RDP failed login | All agents | — |
| **Phase 2 — Attack Patterns** | SSH brute force, RDP brute force, port scan, web scan | Metasploitable3, Windows 11 | T1110, T1046, T1595, T1595.002 |
| **Phase 3 — System Compromise** | User creation, group escalation, sudo abuse, FIM (Linux + Windows) | Metasploitable3, Windows 11 | T1136, T1548, T1070, T1565 |
| **Phase 4 — Advanced Behavior** | vsftpd exploit, reverse shell, cron persistence, scheduled task, malware simulation | Metasploitable3, Windows 11 | T1190, T1059, T1053.003, T1053.005, T1027 |

---

### Phase 4 — Application Security 🗓 Planned

**Repository:** [application-security](https://github.com/wilsonnjoroge/application-security)

OWASP Top 10, threat modelling (STRIDE), DAST/SAST tooling, secure coding practices.

---

### Phase 5 — Cloud Security 🗓 Planned

**Repository:** [cloud-security](https://github.com/wilsonnjoroge/cloud-security)

Cloud IAM hardening, container security, IaC security on AWS, Azure, and Kubernetes.

---

### Phase 6 — Incident Response & DFIR 🗓 Planned

**Repository:** [incident-response](https://github.com/wilsonnjoroge/incident-response)

Full incident response lifecycle from detection through forensic analysis and post-incident hardening.

---

### Bonus — Password Strength Checker

**Repository:** [Password-Strength-Checker](https://github.com/wilsonnjoroge/Password-Strength-Checker)

A full-featured Python/Flask application for real-time password security evaluation. Features entropy analysis, crack-time estimation, HaveIBeenPwned breach detection (k-anonymity), pattern detection (repeats, sequences, keyboard walks), and actionable improvement tips.

**Stack:** Python 3.12, Flask, HTML5, CSS3, Vanilla JS, HaveIBeenPwned API

---

## Scripts & Automation

**Location:** [scripts/auto-scan.sh](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/scripts/auto-scan.sh)

Automated scanning script used across vulnerability assessment engagements to standardise scan execution and output formatting.

---

## Technical Skills

| Category | Tools & Technologies |
|---|---|
| **Security Tools** | Nmap, Nessus, OpenVAS, Nikto, Wireshark, Metasploit, Burp Suite, PhotoRec, Wazuh, Suricata, Hydra |
| **Enumeration** | dirb, gobuster, enum4linux, dig, rpcinfo, manual service enumeration |
| **Detection Engineering** | SIEM rule development, log correlation, MITRE ATT&CK mapping, FIM, IDS integration |
| **Enterprise Platforms** | Oracle SOA Suite, WebLogic, Service Bus, Java EE |
| **Cloud & Infrastructure** | AWS, Docker, Kubernetes, Linux (Kali/Ubuntu), Windows |
| **Languages** | Java (Spring Boot), Python, Bash, C# (ASP.NET Core), Node.js (Express) |
| **Reporting** | Markdown, executive summaries, technical reports, attack chain analysis |

---

## Ethics & Responsible Use

All testing in this portfolio is conducted on intentionally vulnerable systems in isolated lab environments. No unauthorised testing is performed on production systems or third-party infrastructure.

---

## GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=wilsonnjoroge&theme=tokyonight&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-streak-stats.herokuapp.com/?user=wilsonnjoroge&theme=dark)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=wilsonnjoroge&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

<div align="center">

⭐ **If you find my work valuable, please consider starring the projects**

**Wilson Njoroge Wanderi**
*Last Updated: May 2026*

</div>
