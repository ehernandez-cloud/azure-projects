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

## Screenshots

### Resource Group
![Resource Group](Screenshots/RG-creation.png)

### VNet + Subnets
![Subnets](Screenshots/subnets-creation.png)

### NSG Rules (Web + App)
![NSG Web](Screenshots/NSG-Web-inbound-rules.png)
![NSG App](Screenshots/NSG-App-Inbound-Rule.png)

### VM – Overview / Networking / Security Rules
![VM Overview](Screenshots/VM-overview.png)
![VM Networking](Screenshots/VM-networking.png)
![VM Effective NSG Rules](Screenshots/VM-effective-security-rules.png)

### Backup Configuration
![Backup Items](Screenshots/backup-items.png)
![Backup Job](Screenshots/backup-job.png)

### Monitoring + Alerts
![Alert Rule](Screenshots/alert-rule.png)


## ARM/Bicep Templates

## Notes/Learnings
