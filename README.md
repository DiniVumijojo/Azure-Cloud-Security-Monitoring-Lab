
# Azure Cloud Security Monitoring Lab

## Overview

This project demonstrates the deployment, configuration, and monitoring of a secure Linux virtual machine in Microsoft Azure. The lab focuses on implementing cloud security best practices, collecting authentication logs, analyzing security events using Kusto Query Language (KQL), and creating Azure Monitor alerts for automated detection.

The project simulates the responsibilities of a Cloud Security Engineer or SOC Analyst by demonstrating how Azure-native security monitoring can be used to detect and investigate authentication activity.

---

## Objectives

- Deploy a secure Linux virtual machine in Microsoft Azure
- Configure Azure Monitor and Log Analytics
- Collect Linux Syslog using Azure Monitor Agent
- Create and configure Data Collection Rules (DCR)
- Analyze authentication events using KQL
- Create Azure Monitor alert rules
- Demonstrate cloud security monitoring and threat detection

---

## Architecture

```
Internet
      │
      ▼
Network Security Group (NSG)
      │
      ▼
Ubuntu Linux VM
      │
Azure Monitor Agent
      │
      ▼
Data Collection Rule (DCR)
      │
      ▼
Log Analytics Workspace
      │
      ▼
KQL Queries
      │
      ▼
Azure Monitor Alert Rule
```

---

## Technologies Used

- Microsoft Azure
- Ubuntu 24.04 LTS
- Azure Virtual Machines
- Azure Monitor
- Azure Monitor Agent
- Azure Log Analytics
- Azure Monitor Alerts
- Microsoft Entra ID
- Network Security Groups (NSGs)
- SSH
- Kusto Query Language (KQL)

---

## Skills Demonstrated

- Cloud Security
- Azure Administration
- Linux Administration
- Security Monitoring
- Security Event Investigation
- Log Analysis
- KQL Query Development
- Identity and Access Management
- Network Security
- Incident Detection

---

## Key Security Tasks Completed

- Deployed and secured an Azure Linux Virtual Machine
- Configured SSH public key authentication
- Implemented Network Security Groups
- Configured Azure Monitor Agent
- Created Data Collection Rules
- Collected Linux Syslog into Log Analytics
- Investigated SSH authentication events using KQL
- Created Azure Monitor alert rules
- Validated end-to-end cloud security monitoring

---

## Documentation

The complete implementation guide with screenshots and detailed explanations is available here:

📄 Azure_Cloud_Security_Monitoring_Lab_Report.pdf

## Author

**Dini Vumijojo**

Diploma in Information Technology (Infrastructure)

Aspiring Cloud Security Engineer | DevSecOps | Cybersecurity
