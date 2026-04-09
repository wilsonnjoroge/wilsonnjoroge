# Wilson Njoroge Wanderi : Cybersecurity Portfolio. 

> **From Backend Engineer to Security Professional**: A structured, hands-on journey through the complete attack-and-defense lifecycle

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
    <a>
        <img src="https://komarev.com/ghpvc/?username=wilsonnjoroge&label=Profile%20views&color=0e75b6&style=flat" alt="Wilson-Njoroge" />
    </a>
</p>

---

👋 About Me

I’m a Cyber Security & Digital Forensics engineer with a strong foundation in backend and enterprise middleware development. My background spans Java (Spring Boot), Node.js (Express), C# (ASP.Net Core), Oracle SOA Suite, WebLogic, and Service Bus, giving me deep insight into how enterprise systems are designed, integrated, and operated at scale.

Currently pursuing an MSc in Cyber Security & Digital Forensics, I focus on:

    Incident Response & Forensic Analysis — memory acquisition, disk imaging, and evidence preservation

    Vulnerability Assessment & Threat Hunting — identifying weaknesses with an understanding of the systems behind them

    Secure System Design — applying builder’s knowledge to strengthen authentication, integration, and cloud‑native platforms

My unique perspective comes from having built the systems that security practitioners assess. This allows me to bridge the gap between development and defense, ensuring investigations and protections are both technically rigorous and operationally relevant.

---

## Certifications.

| Certification | Issuer | Status |
|--------------|--------|--------|
| Certified in Cybersecurity (CC) | <img src="https://img.shields.io/badge/ISC2-CC-006400?style=for-the-badge&logo=isc2&logoColor=white" alt="ISC2 CC"/> | ✅ Completed |
| Cybersecurity (CCST) | <img src="https://img.shields.io/badge/Cisco-CCST-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="CCST"/> | 🔄 In Progress |
| MSc Cyber Security & Digital Forensics | <img src="https://ouk.ac.ke/sites/default/files/gallery/logo_footer.png" alt="OUK" height="50"/> | 🔄 In Progress |
| CompTIA Security+ | <img src="https://img.shields.io/badge/CompTIA-Security%2B-0096D6?style=for-the-badge&logo=compTIA&logoColor=white" alt="CompTIA Security+" /> | 🔄 In Progress |

---

## Learning Philosophy

I'm building security expertise by following how attacks and defenses actually unfold, progressing through the complete lifecycle rather than jumping to exploitation:

```
┌─────────────────────────────────────────────────────────────┐
│                  SECURITY LIFECYCLE                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  1. IDENTIFY → What's vulnerable and why?                   │
│     (Vulnerability Assessment & Management)                 │
│                                                             │
│  2. EXPLOIT → How are weaknesses actually attacked?         │
│     (Controlled Penetration Testing)                        │
│                                                             │
│  3. DETECT → How do we see attacks happening?               │
│     (SIEM/SOC & Security Monitoring)                        │
│                                                             │
│  4. PREVENT → How do we stop vulnerabilities at the source? │
│     (Application Security & Secure Development)             │
│                                                             │
│  5. SECURE → How do we architect secure environments?       │
│     (Cloud & Infrastructure Security)                       │
│                                                             │
│  6. RESPOND → How do we handle security incidents?          │
│     (Incident Response & Digital Forensics)                 │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

Each phase builds on the previous. This is how security programs mature — and how I'm structuring my learning.

---

# Projects

## 1 - Vulnerability Assessment & Management
**Repository:** [vulnerability-assessment](https://github.com/wilsonnjoroge/vulnerability-assessment) | ✅ **Completed**

Comprehensive vulnerability assessment of intentionally vulnerable systems using enterprise-grade tools and methodology. Full 7-phase assessment lifecycle: pre-engagement through prioritised remediation reporting.

**What this demonstrates:**
- Cross-scanner validation (Nmap NSE + OpenVAS + Nessus + Nikto)
- CVE/CVSS analysis and risk prioritisation beyond raw scanner output
- Manual service enumeration across 13+ services
- Professional reporting: executive summary, technical report, attack chain analysis
- False positive identification and assessor judgement

**Target 1: Metasploitable2**
- 47 vulnerabilities identified across 23 services
- 14 Critical findings, 10 with confirmed public exploits
- 6 independent attack paths to full system compromise documented
- 4-scanner cross-validation with false positive assessment

<table>
  <tr>
    <th colspan="2" align="center">Metasploitable2</th>
  </tr>
  <tr>
    <th>Document</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Executive Summary</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/executive-summary-report/metasploitable2-executive-summary-report.md">View Executive Summary Report</a></td>
  </tr>
  <tr>
    <td>Full Technical Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/technical-report/metasploitable2-full-technical-report.md">View Full Technical Report</a></td>
  </tr>
  <tr>
    <td>Attack Chain Analysis</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/analysis/attack-chain-analysis.md">View Attack Chain Analysis Report</a></td>
  </tr>
  <tr>
    <td>OpenVAS Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-openvas-report.md">View OpenVAS Report</a></td>
  </tr>
  <tr>
    <td>Nessus Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nessus-report.md">View Nessus Report</a></td>
  </tr>
  <tr>
    <td>Nmap Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nmap-report.md">View Nmap Report</a></td>
  </tr>
</table>

<!--
| Document | Link |
|----------|------|
| Executive Summary | [View Executive Summary Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/executive-summary-report/metasploitable2-executive-summary-report.md) |
| Full Technical Report | [View Full Technical Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/technical-report/metasploitable2-full-technical-report.md) |
| Attack Chain Analysis | [View Attack Chain Analysis Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/analysis/attack-chain-analysis.md) |
| OpenVAS Report | [View OpenVAS Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-openvas-report.md) |
| Nessus Report | [View Nessus Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nessus-report.md) |
| Nmap Report | [View Nmap Report](https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nmap-report.md) |
-->

**In progress:** DVWA, OWASP Juice Shop

<!--
**Target 2: DVWA**

<table>
  <tr>
    <th colspan="2" align="center">DVWA</th>
  </tr>
  <tr>
    <th>Document</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Executive Summary</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/executive-summary-report/metasploitable2-executive-summary-report.md">View Executive Summary Report</a></td>
  </tr>
  <tr>
    <td>Full Technical Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/technical-report/metasploitable2-full-technical-report.md">View Full Technical Report</a></td>
  </tr>
  <tr>
    <td>Attack Chain Analysis</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/analysis/attack-chain-analysis.md">View Attack Chain Analysis Report</a></td>
  </tr>
  <tr>
    <td>OpenVAS Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-openvas-report.md">View OpenVAS Report</a></td>
  </tr>
  <tr>
    <td>Nessus Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nessus-report.md">View Nessus Report</a></td>
  </tr>
  <tr>
    <td>Nmap Report</td>
    <td><a href="https://github.com/wilsonnjoroge/vulnerability-assessment/blob/main/metasploitable2/05-reporting/vulnerability-scanning-reports/metasploitable2-nmap-report.md">View Nmap Report</a></td>
  </tr>
</table>
-->

---

## 2 - Penetration Testing
**Repository:** [penetration-testing](https://github.com/wilsonnjoroge/penetration-testing) | 🗓 **Planned**

Controlled exploitation of validated vulnerabilities from Phase 1. Demonstrates the difference between theoretical vulnerability and confirmed exploitability — and what real-world impact looks like.

---

## 3 - Password Strength Checker
**Repository:** [Password-Strength-Checker](https://github.com/wilsonnjoroge/Password-Strength-Checker) | ✅ **Completed**


    A full‑featured cybersecurity project built with Python and Flask to evaluate password security in real time. 
    The application provides entropy analysis, crack‑time estimation, and breach detection using the HaveIBeenPwned API, 
    while also checking against a local blocklist of common passwords.

    Key Features:
    Real‑time feedback with an animated strength meter and per‑criterion checklist

    Entropy calculation and human‑readable crack‑time estimation

    Detection of weak patterns (repeated, sequential, keyboard walks)

    Integration with HaveIBeenPwned (k‑anonymity lookup) for breach status

    Actionable improvement tips and session history for user learning


    Tech Stack: Python 3.12, Flask, HTML5, CSS3, Vanilla JS, HaveIBeenPwned API


    Impact: 

    This project demonstrates practical cybersecurity awareness, backend development skills, and user‑focused design. It’s designed as both a portfolio piece and a tool to educate users on building stronger, more resilient passwords.
    






---
<!--
### Phase 3 — SIEM & Detection Engineering
**Repository:** [siem-detection-lab](https://github.com/wilsonnjoroge/siem-detection-lab) | 🗓 **Planned**

Detection rule development and log correlation using ELK Stack. Will use Phase 2 attack telemetry as the detection target — closing the loop between offensive findings and defensive visibility.

---

### Phase 4 — Application Security
**Repository:** [application-security](https://github.com/wilsonnjoroge/application-security) | 🗓 **Planned**

OWASP Top 10 analysis, threat modelling (STRIDE), and secure code review. Maps web vulnerabilities found in Phase 1 to root cause insecure coding patterns.

---

### Phase 5 — Cloud Security
**Repository:** [cloud-security](https://github.com/wilsonnjoroge/cloud-security) | 🗓 **Planned**

Cloud IAM hardening, container security, and IaC security on AWS, Azure, and Kubernetes.

---

### Phase 6 — Incident Response & DFIR
**Repository:** [incident-response](https://github.com/wilsonnjoroge/incident-response) | 🗓 **Planned**

Full incident response lifecycle from initial detection through forensic analysis and post-incident hardening.

---

-->

## Technical Skills

**Security tools:** Nessus, OpenVAS, Nmap, Nikto, Wireshark, Metasploit, Burp Suite  
**Enterprise platforms:** Oracle SOA Suite, WebLogic, Service Bus, Java EE  
**Cloud & infrastructure:** AWS, Docker, Kubernetes, Linux (Kali/Ubuntu), Windows  
**Languages:** Java(SpringBooot), Python, Shell(Bash), C#(ASP.Net Core, NodeJs(Express)  

---

## Ethics & Responsible Use

All testing in this portfolio is conducted on intentionally vulnerable systems in isolated lab environments. No unauthorised testing is performed on production systems or third-party infrastructure.

---

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=wilsonnjoroge&theme=tokyonight&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=wilsonnjoroge&theme=dark)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=wilsonnjoroge&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

<div align="center">
  <p><strong>⭐ If you find my work valuable, please consider starring the projects</strong></p>
    <p><strong>Wilson Njoroge Wanderi</strong></p>
  <p><em>Last Updated: 19th February 2026</em></p>
</div>
