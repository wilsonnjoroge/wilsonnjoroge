# Wilson Njoroge Wanderi — Cybersecurity Portfolio

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

I'm a Cybersecurity & Digital Forensics engineer with a strong foundation in backend and enterprise middleware development — Java (Spring Boot), Node.js, C# (ASP.NET Core), Oracle SOA Suite, WebLogic, and Service Bus. I've spent years building the systems that security practitioners assess, which gives me a rare perspective: I understand both how systems break and why they were built that way.

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
│     Vulnerability Assessment & Management          ✅ Active │
│                                                             │
│  2. EXPLOIT   → How are weaknesses actually attacked?       │
│     Controlled Penetration Testing              🔄 Planned  │
│                                                             │
│  3. DETECT    → How do we see attacks happening?            │
│     SIEM / SOC & Security Monitoring            🔄 Planned  │
│                                                             │
│  4. PREVENT   → How do we stop vulnerabilities at source?   │
│     Application Security & Secure Development   🔄 Planned  │
│                                                             │
│  5. SECURE    → How do we architect secure environments?    │
│     Cloud & Infrastructure Security             🔄 Planned  │
│                                                             │
│  6. RESPOND   → How do we handle security incidents?        │
│     Incident Response & Digital Forensics       🔄 Planned  │
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
    <td><a href="https://github.com/wilsonnjoroge/Nikto-Metasploitable-Vulnerability-Assessment/blob/main/05-reporting/metasploitable2-nikto-report.md">Technical Report</a></td>
  </tr>
  <tr>
    <td>🖥 Manual Enumeration</td>
    <td><a href="https://github.com/wilsonnjoroge/Manual-Enumeration-Metasploitable">Manual Enumeration Repo</a></td>
    <td>13 services manually enumerated: SSH, FTP, Telnet, SMTP, DNS, HTTP, Tomcat, MySQL, PostgreSQL, RPC/NFS, Java RMI, X11, Web</td>
    <td><a href="https://github.com/wilsonnjoroge/Manual-Enumeration-Metasploitable/blob/main/05-reporting/metasploitable2-full-technical-report.md">Technical Report</a></td>
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

### Phase 3 — SIEM & Detection Engineering 🗓 Planned

**Repository:** [siem-detection-lab](https://github.com/wilsonnjoroge/siem-detection-lab)

Detection rule development and log correlation using ELK Stack. Will use Phase 2 attack telemetry as the detection target.

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
| **Security Tools** | Nmap, Nessus, OpenVAS, Nikto, Wireshark, Metasploit, Burp Suite, PhotoRec |
| **Enumeration** | dirb, gobuster, enum4linux, dig, rpcinfo, manual service enumeration |
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
*Last Updated: April 2026*

</div>
