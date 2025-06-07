# 🚀 Azure Infrastructure Assignment – 3

This repository documents the Azure identity, access management, security, and automation tasks carried out as part of the **Infrastructure Assignment 3**.

---

## 📁 Files Included

- `azure-commands.txt` – Azure CLI and PowerShell command references  
- `README.md` – This file  

---

## ✅ Tasks Implemented

### 1. 🔍 Azure Subscriptions & Entra ID
- Observed available subscriptions using `az account show`
- Checked or created Azure Entra ID tenant
- Reviewed tenant properties in the Azure Portal

### 2. 👥 User & Group Management
- Created test users and groups in Entra ID
- Used Portal + Azure CLI for identity provisioning

### 3. 🧾 Role-Based Access Control (RBAC)
- Assigned Reader and Contributor roles to users  
- Created a **custom role** with limited permissions and assigned it

### 4. 📜 Azure Policies
- Created and assigned policies at the **subscription level**
  - Enforced resource tagging
  - Controlled region-based deployments

### 5. 🔐 Azure Key Vault
- Created a Key Vault using CLI
- Stored and retrieved secrets securely
- Configured access policies to allow limited user/app access

### 6. 💻 Virtual Machines with CLI & PowerShell
- Provisioned VMs from both Azure CLI and PowerShell
- Configured network interface, public IP, and OS disk

### 7. 📦 Backup Configuration
- Daily backup of VM scheduled at 3:00 AM using Recovery Services Vault  
- Retention policies configured  
- Alerts created for **CPU > 80%** usage with email notifications

---

## ⚠️ Note

This submission includes written documentation and simulated code references. Some resources were illustrated using mockups due to subscription constraints. A **live demo can be provided if required**.

---

## 👩‍💻 Submitted By

**Lavina Sevani**  
B.Tech CSE, Poornima Institute of Engineering & Technology  
📅 Assignment-3 | June 2025
