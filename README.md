# wazuh-fim-soc-homelab
Hands-on SOC File Integrity Monitoring (FIM) lab using Wazuh SIEM/XDR across Linux and Windows endpoints.
Wazuh File Integrity Monitoring (FIM) SOC Home LabThis project demonstrates how a SOC analyst uses Wazuh SIEM/XDR to detect unauthorized file changes across Linux (Kali) and Windows Server 2022 endpoints. The lab includes configuration, attacker simulation, alert analysis, MITRE mapping, and SOC investigation workflow.
🔧 Tools & Environment
Wazuh Manager (Ubuntu 26.04)
Wazuh Dashboard & Indexer
Kali Linux endpoint
Windows Server 2022 endpoint
📁 FIM ConfigurationLinux (Kali)Monitored directory:
<directories realtime="yes" whodata="yes" report_changes="yes">/home/</directories>
Windows Server 2022
Monitored directory:
<directories realtime="yes" whodata="yes" report_changes="yes">C:\Users\Public</directories>
🛡️ Attack Simulation
File creation, modification, deletionTimestamp manipulationUnauthorized changes to academic recordsFolder creation and deletion
📊 SOC Investigation Workflow
Alert triage (timestamp, agent, file path, hashes, user)MITRE ATT&CK mapping:T1565.001 – Data ManipulationT1070.004 – Indicator RemovalT1485 – Data Destruction
Severity classification
Response validation
📌 Skills Demonstrated
File Integrity Monitoring (FIM)SOC Analysis
Detection Engineering
Incident Response
Log Analysis
Linux & Windows Security
📎 Files Included
Full lab report (DOCX)
Linux & Windows ossec.conf
Screenshots of alerts and dashboard
