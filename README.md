# CYB2100 Cyber Defense Exam Project

This repository contains my exam submission for the course CYB2100 Cyber Defense.

The project focuses on defensive cybersecurity techniques, threat analysis, malware investigation, and security monitoring using SIEM tools.

Overview

The exam is divided into three main parts.

Part 1 – Threat Analysis and Malware Investigation

This section focuses on phishing attacks, defensive measures, and malware analysis. It includes identification of security controls based on MITRE ATT&CK, analysis of attacker techniques used to bypass defenses, and examination of a malicious document containing macros. The analysis shows how the malware executes through Document_Open and uses Windows API functions such as URLDownloadToFileA and ShellExecuteA to download and execute a payload.

The section also includes development of a custom YARA rule using ClamAV to detect the malware based on specific indicators such as API calls and file names.

Part 2 – SIEM and Log Analysis

This section covers Security Information and Event Management (SIEM) concepts and practical log analysis. It includes a comparison between Wazuh and Splunk, highlighting differences in cost, flexibility, and usability.

Practical analysis was performed using the BOTS v1 dataset in Splunk. Tasks included identifying DNS activity, analyzing HTTP traffic volume over time, detecting potential lateral movement, and investigating possible command-and-control communication. SPL queries were used to extract and visualize relevant security data.

Part 3 – Governance and Advanced Threats

This section focuses on regulatory requirements and advanced threat actors. It includes analysis of the NIS2 directive and its implications for critical infrastructure organizations, with emphasis on risk management, incident reporting, and supply chain security.

The section also examines the threat actor Volt Typhoon and its use of Living off the Land techniques. The analysis highlights how attackers use legitimate tools such as PowerShell and WMI to avoid detection, and discusses risks related to IT and OT environments, particularly in critical infrastructure sectors.

Technologies Used

Ubuntu Linux virtual machine
ClamAV and YARA
oletools (olevba)
Splunk SIEM
BOTS v1 dataset
MITRE ATT&CK framework

Key Learning Outcomes

This project demonstrates understanding of phishing and social engineering attacks, malware execution and detection techniques, development of YARA signatures for threat detection, practical SIEM analysis using real datasets, identification of lateral movement and command-and-control activity, and knowledge of regulatory frameworks such as NIS2.

Files

254_CYB2100_Eksamen.pdf – Full exam submission

Disclaimer

This project was developed as part of an academic exam and is intended for educational purposes only.

Author

Bachelor student in Cybersecurity
Høyskolen Kristiania
