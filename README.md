# 🛡️ Hey there, I'm Vatsayu | Cyber Security & Blue Team Operations

An analytical, hands-on Blue Team Specialist currently executing an intensive, metrics-driven **30-Day SOC Engineering & Incident Response Sprint**. Backed by a strong baseline in networking architecture, Linux systems administration, and core defensive protocols.

---

### 🚀 Active Sprint: 30-Day Blue Team Operations Portfolio
I am currently documenting live engineering and triage environments. Follow my daily progress, raw analytical findings, and formal incident reports here:
👉 **[View My Live SOC Portfolio Repository](https://github.com/vatsayu/SOC-Portfolio)**

---

## 🏗️ Core Laboratory Architecture (4 Production Projects)
To demonstrate structural hands-on competency to hiring managers, my local virtual environment mirrors enterprise perimeter security architectures. Each project is documented with explicit deployment phases, alert thresholds, and triage logs.

### 🛡️ Project 1: SafeLine Web Application Firewall (WAF) Lab
* **Objective:** Deploy a Web Application Firewall to actively shield web traffic interfaces and mitigate application-layer exploits.
* **Environment Components:** Ubuntu 22.04 LTS VM, Docker, Docker-Compose, DVWA (Damn Vulnerable Web Application), SafeLine WAF.
* **Practical Tasks:** - Simulated a malicious attacker executing an unauthenticated SQL Injection (`1' OR '1'='1`) attack payload against standard application input fields.
  - Deployed SafeLine WAF reverse-proxy configurations over Port 80 to catch malicious patterns and return explicit red-flag access violations.
  - Engineered Anti-Bot Rate Limiting infrastructure restricting client traffic down to 20 requests per second to counter automated Denial of Service (DoS) floods.
* **Documentation Links:** [Setup Log & Logs Analysis]((https://github.com/vatsayu/SOC_Lab/tree/main/Projects/Project-1-SafeLine-WAF))

### 📊 Project 2: Wazuh SIEM Security Intelligence Lab
* **Objective:** Centralize telemetry and monitor active file-integrity states via an enterprise-grade SIEM platform.
* **Environment Components:** Ubuntu 22.04 (Wazuh Manager node Appliance), Windows 10/11 Endpoint (Wazuh Agent), Oracle VirtualBox Host-Only networking.
* **Practical Tasks:** - Automated deployment of the centralized security monitoring console via the pre-built Wazuh Appliance OVA framework.
  - Installed and authenticated local monitoring agents on guest endpoints to feed critical operating system event streams into the SIEM dashboard.
  - Configured custom File Integrity Monitoring (`<syscheck>`) criteria inside the agent `ossec.conf` file to dynamically trigger alerts on unauthorized file alterations across sensitive file paths.
* **Documentation Links:** [SIEM Dashboard Configurations](https://github.com/vatsayu/SOC_Lab/tree/main/Projects/Project%202%20-%20Wazuh%20SIEM)

### 🧱 Project 3: pfSense Network Firewall & Traffic Rules Engine
* **Objective:** Configure a stateful firewall router to isolate internal localized boundaries from unauthenticated networks.
* **Environment Components:** pfSense Firewall OS, Ubuntu Client Node (Protected Local Area Network Side), Kali Linux Endpoint (Simulated WAN External Space).
* **Practical Tasks:** - Architected dual virtual switch network interfaces inside VirtualBox isolating the protected LAN subnet from the exposed WAN subnet zone.
  - Provisioned strict Top-to-Bottom processing rules allowing inbound Layer 7 HTTP connections (Port 80 TCP) while matching and blocking raw ICMP Echo requests (Pings).
  - Implemented advanced rate-limiting control options inside stateful firewall structures to flag and restrict high-velocity brute-force floods.
* **Documentation Links:** [Firewall Rule Blueprints](https://github.com/vatsayu/SOC_Lab/tree/main/Projects/Project%203%20-%20pfSense%20Firewall)

### 🤖 Project 4: AI-Powered Autonomous SOC Analyst Agent
* **Objective:** Develop an automated initial pipeline using Large Language Models to evaluate log data against active playbooks.
* **Environment Components:** Ubuntu Server, Airia AI API Framework, Python 3 Development Tools, Kali Linux Network Ingestion.
* **Practical Tasks:** - Coded a custom Python automation script natively connecting endpoint log data streams to remote text-generation engines using standard API calls.
  - Injected an operational SOC Playbook into the system prompt framework to train the AI to parse raw text streams into discrete structural variables.
  - Tested classification accuracy against authentication logs to successfully isolate SSH Brute-Force sequences, quantify severity levels, and map tactical response plans.
* **Documentation Links:** [Python Scripts & AI Output Logs](https://github.com/vatsayu/SOC_Lab/tree/main/Projects/Project%204%20-%20AI%20SOC%20Agent)

---

### 📊 Portfolio Targets & Competencies
* **Network Forensics:** Multi-stage packet triage using Wireshark to track C2 beaconing frequencies, cleartext credential leakage, and exfiltration vectors.
* **SIEM Engineering:** Deploying local instances, structuring parsing pipelines, and writing production-ready SPL queries mapped to MITRE ATT&CK techniques.
* **Endpoint Inspection & Auditing:** Deciphering host telemetry using Windows Security Event IDs, Sysmon process-creation logs, and Linux CLI forensic commands.
* **Incident Analysis:** Structuring enterprise-grade triage reports for malicious phishing (`.eml`) payloads and active web applications attacks (SQLi/XSS).

---

### 🛠️ Technical Arsenal

| Domain | Tools & Technologies |
| :--- | :--- |
| **SIEM & Monitoring** | Splunk Enterprise, Wazuh SIEM, Search Processing Language (SPL) |
| **Traffic & Analysis** | Wireshark, pfSense Firewall, SafeLine WAF, Network Protocols (TCP/IP, DNS) |
| **Telemetry & Auditing** | Windows Event Logs, Sysmon, Snort/Suricata Alerts |
| **Automation & Dev** | Python 3, Airia AI Framework, Linux Bash Scripting |
| **Frameworks** | MITRE ATT&CK, Cyber Kill Chain, NIST SP 800-61 |

---

📫 **Let's Connect:** [https://www.linkedin.com/in/ayush-vats-936b71238/] | [vatsayu31@gmail.com]
