# 🛡️ Jesse Lance Barreto — Cybersecurity Portfolio

**SOC & detection engineering · Cloud security (Azure) · AI/LLM security**

Postgraduate Cybersecurity & Threat Management student at Seneca Polytechnic (graduating December 2026) and IT Systems & Programmer Co-op in the Ontario Public Service. Before that, I spent several years in 24/7 IT operations. As a NOC Administrator at Milestone Technologies, supporting ZeniMax Media / Bethesda Softworks, I caught a DDoS attack on *The Elder Scrolls Online* by spotting a player-population anomaly in Grafana before any upstream alert fired.

This portfolio collects my hands-on security work: detection engineering, incident investigation, vulnerability assessment, cloud security and LLM application security.

---

## 📂 Featured Projects (2026)

| Project | What I did | Tools & Skills |
|---|---|---|
| [**AI Chatbot Security Assessment**](https://github.com/JesseLanceB/llm-chatbot-security) (capstone, team of 5) | Threat-modelled a self-hosted LLM chatbot with STRIDE across five components and mapped requirements to PIPEDA, ISO/IEC 27001 and NIST CSF. Confirmed indirect prompt injection, system prompt leakage and an unauthenticated model API; tested XSS via model output (LLM05), ruling out reflected and stored XSS. Published my own [Docker image](https://hub.docker.com/r/jlib3027/chatbot-ollama). | Open WebUI, Ollama, Phi-3, Docker, Kali, STRIDE, OWASP LLM Top 10 |
| **Detection Engineering Labs** | Built a detection for masquerading (MITRE ATT&CK T1036.003) using the Sysmon `OriginalFileName` field; wrote YARA rules from threat intel on the ClickFix generator campaign; mapped CAR analytics for port scanning and UAC bypass. | Sysmon, YARA, MITRE ATT&CK, CAR |
| **Wazuh EDR Home Lab** | Deployed a Wazuh manager, indexer and dashboard, fixed systemd start-up timeouts and a port-binding failure, and enrolled a Windows 11 endpoint agent. | Wazuh, Linux, systemd, Windows 11, VMware |
| **Network & Memory Forensics** | Investigated CyberDefenders incidents from packet captures and memory images: HawkEye keylogger (24/24), Tomcat Takeover (8/8), PsExec lateral movement and ActiveMQ CVE-2023-46604, each documented with a timeline, IOC table and recommendations. | Wireshark, NetworkMiner, Volatility |
| **AWS Cloud Security Lab** | Built a segmented VPC with security groups, NACLs, WAF, GuardDuty and Suricata IDS, shipping logs with Filebeat into Elasticsearch/Kibana. | AWS, Suricata, ELK, Filebeat |
| **Threat Intelligence Visualization** | Turned AlienVault OTX exports (STIX, CSV) into pandas dataframes and plotly charts, and compared indicator collections in code. | Python, pandas, plotly, STIX |

## 🚧 In Progress

- **LLM Security Testing:** automated promptfoo tests for prompt injection and system prompt leakage, run before and after hardening, extending my capstone. *Target: November 2026*
- **Microsoft Sentinel Detection Lab:** KQL detections mapped to MITRE ATT&CK in Azure. *Target: December 2026*

## 🗂️ Earlier Work

| Project | Description | Tools & Skills |
|---|---|---|
| [Security Audit](https://jesselanceb.github.io/Security-Audit/) | Internal security audit (Google Cybersecurity Certificate) | Vulnerability assessment, compliance |
| [Incident Report Analysis](https://jesselanceb.github.io/Incident-Report-Analysis/) | Incident analysis (Google Cybersecurity Certificate) | Root cause analysis |
| [Permission Management in Linux](https://jesselanceb.github.io/Permission-management-in-Linux/) | File permissions and least privilege (Google Cybersecurity Certificate) | Linux, chmod |
| [Apply Filters to SQL Queries](https://jesselanceb.github.io/Apply-Filters-to-SQL-queries/) | Security investigation queries (Google Cybersecurity Certificate) | SQL |
| [Vulnerability Assessment](https://jesselanceb.github.io/Vulnerability-Assessment/) | Risk assessment (Google Cybersecurity Certificate) | Risk assessment |
| [SQL Server Practice Database](https://github.com/JesseLanceB/jtsd-coop-prep) | Designed and seeded a relational database and wrote query drills (joins, aggregates, transactions) | SQL Server, T-SQL, Git |

---

## 🧠 Skills & Tools

- **SIEM, EDR & Monitoring:** Splunk, Wazuh, Elasticsearch/Kibana, Grafana, CheckMK, Suricata
- **Detection & Threat Intel:** Sysmon, YARA, MITRE ATT&CK, CAR, AlienVault OTX, STIX/OpenIOC
- **Offensive & Assessment:** Kali Linux, Nmap, Metasploit, OpenVAS, STRIDE threat modelling, OWASP LLM Top 10
- **Forensics:** Wireshark, NetworkMiner, Volatility, FTK Imager, SIFT Workstation
- **Cloud & Identity:** Microsoft Azure (Entra ID, Azure SQL Managed Instance), AWS (EC2, VPC, WAF, GuardDuty)
- **ITSM:** BMC Remedy, Jira Service Management, ServiceNow
- **Scripting & Data:** Python (pandas, plotly), SQL, PowerShell
- **Platforms:** Windows, Linux, macOS, Docker, VMware

## 🏆 Certifications

- [Google Cybersecurity Professional Certificate](https://www.credly.com/badges/2cebc36a-a3bf-4d09-85a5-10234b31dadb/linked_in_profile)
- [Career Essentials in Cybersecurity — Microsoft & LinkedIn](https://www.linkedin.com/learning/certificates/a0f381e7c9831f3341eebc0b51c864b734073da82f2bc42b78fab1b9a31eae77)
- [IBM IT Support Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/SZGMZ7B7A238)

## 🎓 Education

- **Postgraduate Certificate, Cybersecurity and Threat Management**, Seneca Polytechnic, Toronto (December 2026)
- **Bachelor of Technology, Electronics Technology** (WES-evaluated as equivalent to a Canadian bachelor's degree)

## 📫 Contact

- LinkedIn: [Jesse Lance Barreto](https://www.linkedin.com/in/jesse-lance-barreto-b036b0123/)
- Email: barretojesselance3027@gmail.com
