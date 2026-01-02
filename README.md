# AZ-104 Azure Administrator Portfolio Project

## 📌 Overview

This project demonstrates hands-on Azure Administrator skills aligned with the **AZ-104 certification**.  
It provisions a secure, monitored Azure environment using **Terraform (Infrastructure as Code)**.

## 🎯 Objectives

- Implement Azure governance and identity controls
- Deploy and manage compute, storage, and networking
- Enable monitoring, alerting, and backups
- Use Terraform for repeatable deployments

## 🏗 Architecture

![Architecture](diagrams/architecture.png)

## 🧰 Technologies Used

- Microsoft Azure
- Terraform
- Azure Monitor & Log Analytics
- Azure Backup
- Azure RBAC & Policies

## 📂 Project Structure

terraform/
network.tf
compute.tf
storage.tf
monitoring.tf
backup.tf
rbac.tf
policy.tf

markdown
Copy code

## 🚀 Deployment Steps

1. Clone the repository
2. Login to Azure
   ```bash
   az login
   Initialize Terraform
   ```

bash
Copy code
terraform init
Apply infrastructure

bash
Copy code
terraform apply
🔐 Security & Governance
RBAC roles applied per resource group

Azure Policies enforce tagging and VM size restrictions

Secure VM access using Azure Bastion

📊 Monitoring & Backup
Centralized logging via Log Analytics

CPU and disk alerts

Automated VM backups using Recovery Services Vault

📚 AZ-104 Skills Demonstrated
✔ Identity & Governance
✔ Virtual Networking
✔ Compute Management
✔ Storage Management
✔ Monitoring & Backup

👤 Author
Dennis Joseph Reyes
Azure Administrator | Cloud Security & DevOps Enthusiast
