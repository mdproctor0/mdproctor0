# Marquell Proctor
### Cloud Engineer · Azure · M365 · Infrastructure as Code · Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/marquell-proctor-cyber)
[![AZ-900](https://img.shields.io/badge/Microsoft-AZ--900-0078D4?style=flat-square&logo=microsoft-azure)](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=flat-square&logo=comptia)](https://www.comptia.org/certifications/security)
[![AZ-104](https://img.shields.io/badge/AZ--104-In%20Progress-orange?style=flat-square&logo=microsoft-azure)](https://learn.microsoft.com/en-us/certifications/azure-administrator/)
[![Clearance](https://img.shields.io/badge/Clearance-TS%2FSCI%20%7C%20FSP-darkgreen?style=flat-square)](/)

---

## About Me

I design, secure, and operate cloud infrastructure in Azure and Microsoft 365. My work sits at the intersection of cloud engineering and security — building environments that are architected correctly from the start rather than secured after the fact.

I specialize in identity architecture, network segmentation, infrastructure as code, M365 administration, and cloud automation. On the security side I've built threat hunting playbooks, automated STIG remediation at scale, and operationalized vulnerability management workflows.

TS/SCI · Full-Scope Polygraph · Active

---

## What I Work With

```
Cloud Platform    │ Microsoft Azure · Microsoft 365 · Entra ID · Azure Monitor · Sentinel
Identity          │ RBAC · Conditional Access · PIM · Azure Policy · Management Groups
M365 Admin        │ Exchange Online · SharePoint · Teams · Purview · DLP · eDiscovery
Infrastructure    │ Terraform · ARM Templates · PowerShell · Azure CLI · Python
Security Ops      │ DISA STIGs · Threat Hunting · KQL · Vulnerability Management
```

---

## Projects

### ☁️ [Azure Infrastructure](https://github.com/mdproctor0/az104-labs/blob/main/README.md)

| Repository | What It Builds | Services |
|---|---|---|
| [az104-identity-governance](https://github.com/mdproctor0/az104-labs/tree/main/identity-governance) | Zero-trust identity architecture for a financial services environment | Entra ID · RBAC · Conditional Access · Azure Policy |
| [az104-networking](https://github.com/mdproctor0/az104-labs/tree/main/networking) | Secure multi-tier network with segmentation and private connectivity | VNet · NSG · Bastion · Private DNS · Load Balancers |
| [az104-storage](https://github.com/mdproctor0/az104-labs/tree/main/storage) | Enterprise storage with lifecycle automation and access controls | Blob · File Sync · SAS Tokens · Private Endpoints |
| [az104-compute](https://github.com/mdproctor0/az104-labs/tree/main/compute) | Highly available compute deployed entirely through infrastructure as code | VMSS · Availability Zones · ARM Templates · App Service |
| [az104-monitoring](https://github.com/mdproctor0/az104-labs/tree/main/monitoring) | Full observability and backup stack for production workloads | Log Analytics · KQL · Azure Monitor · Recovery Vault |

---

### 🏗️ Infrastructure as Code — Terraform

| Repository | What It Builds | Tech |
|---|---|---|
| [secure-azure-foundation-terraform](https://github.com/mdproctor0/secure-azure-foundation-terraform) | Secure-by-default Azure baseline — private VM, deny-by-default NSGs, NAT Gateway, Bastion, Log Analytics | Terraform · AzureRM |
| [azure-secure-storage](https://github.com/mdproctor0/azure-secure-storage) | Hardened Azure Storage Account — HTTPS only, TLS 1.2, public access disabled, built from scratch | Terraform · AzureRM |

---

### 📧 Microsoft 365 Administration

| Repository | What It Covers | Tools |
|---|---|---|
| [m365-cloud-engineering-labs](https://github.com/mdproctor0/m365-cloud-engineering-labs) | 7-lab series covering the full M365 admin stack in an E5 developer tenant | PowerShell · PnP · Graph API |

**Labs included:**

| Lab | Topic |
|-----|-------|
| Lab 01 | Exchange Online — shared mailboxes, distribution groups, transport rules |
| Lab 02 | Email Authentication — SPF, DKIM, DMARC |
| Lab 03 | Teams Governance — meeting policies, messaging policies, app controls |
| Lab 04 | Purview Compliance — eDiscovery, retention policies, legal holds |
| Lab 05 | Conditional Access + DLP — named locations, MFA enforcement, credit card DLP |
| Lab 06 | Graph API + Bulk PowerShell — mailbox size report, MFA status audit |
| Lab 07 | SharePoint Online — team sites, sharing governance, unique permissions |

---

### 🔐 Security Engineering

| Repository | What It Solves | Tech |
|---|---|---|
| [DISA-STIG-Remediation](https://github.com/mdproctor0/DISA-STIG-Remediation) | Automated STIG compliance remediation at scale | PowerShell |
| [threat-hunting-scenario-tor](https://github.com/mdproctor0/threat-hunting-scenario-tor) | Threat hunting playbook for TOR network exfiltration activity | KQL · Sentinel |
| [Vulnerability-Management-Simulation](https://github.com/mdproctor0/Vulnerability-Management-Simulation) | End-to-end vulnerability management lifecycle — 81% vulnerability reduction | Scanning · Remediation |
| [Port-Entry-pt1](https://github.com/mdproctor0/Port-Entry-pt1) | Network penetration testing and enumeration scenario | Network Security |

---

### 🐍 Python + Automation

| Repository | What It Does | Tech |
|---|---|---|
| [azure-resource-inventory](https://github.com/mdproctor0/azure-resource-inventory) | Inventories all Azure resources across a subscription — exports timestamped CSV report, surfaces untagged resources | Python · Azure SDK · Graph API |
| [cloud-resume-frontend](https://github.com/mdproctor0/cloud-resume-frontend) | Serverless resume with visitor counter API | Python · Azure Functions · Cosmos DB |

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| AZ-900 Azure Fundamentals | Microsoft | ✅ Certified |
| CompTIA Security+ CE | CompTIA | ✅ Certified |
| AZ-104 Azure Administrator | Microsoft | 🔄 July 2026 |

---

*Each repository includes a README documenting the business problem, architecture decisions, and production considerations. Built from scratch — not tutorials.*
