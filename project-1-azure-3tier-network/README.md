# Project 1 — Azure 3-Tier Network + VM + Backup

This project demonstrates the deployment of a secure 3-tier network architecture in Azure using Virtual Networks, Subnets, NSGs, Azure VM, Backup, and Monitoring.

## Architecture Overview
- VNet with 3 subnets: Web, App, Data
- NSGs controlling traffic between tiers
- A virtual machine hosted in the Web subnet
- Azure Backup using a Recovery Services Vault
- Monitoring with Azure Monitor + Alerts

## What This Project Covers
- Creating a VNet and subnets
- Deploying NSGs and rules
- Deploying and connecting a VM
- Configuring Backup
- Enabling monitoring and alerts
- Documenting the project with screenshots

## Screenshots

### Resource Group
![RG](Screenshots/RG-creation.png)

### VNet + Subnets
![Subnets](Screenshots/subnets-creation.png)

### NSG-Web
![NSG Web](Screenshots/NSG-Web-inbound-rules.png)

### NSG-App
![NSG App](Screenshots/NSG-App-Inbound-Rule.png)

### Virtual Machine Overview
![VM Overview](Screenshots/VM-overview.png)

### VM Networking (Web Subnet)
![VM Networking](Screenshots/VM-networking.png)

### VM Effective Security Rules
![VM Effective Rules](Screenshots/VM-effective-security-rules.png)

### Recovery Services Vault Overview
![RSV Overview](Screenshots/RSV-overview.png)

### VM Backup Configuration
![Backup Config](Screenshots/VM-backup-config.png)

### Backup Job Status
![Backup Job](Screenshots/VM-backup-job.png)

### VM Diagnostic Settings
![VM Diagnostics](Screenshots/VM-diagnostics.png)

## ARM/Bicep Templates

## Notes/Learnings
