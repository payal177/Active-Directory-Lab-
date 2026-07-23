![Windows Server](https://img.shields.io/badge/Windows_Server-2022-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-Workstation-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-AD_DS-0A66C2?style=for-the-badge)
![PowerShell](https://img.shields.io/badge/PowerShell-Administration-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

# 🏢 Enterprise Active Directory Lab

<p align="center">

**Windows Server 2022 | VMware Workstation | Active Directory | DNS | DHCP | Group Policy | PowerShell**

</p>

---

> 🚀 A complete Enterprise Active Directory Infrastructure project built using **Windows Server 2022** and **VMware Workstation**, demonstrating real-world Windows Administration, Active Directory management, DNS, DHCP, Group Policy, File Server configuration, PowerShell administration, and enterprise troubleshooting.

---

## 📖 Project Overview

This project demonstrates the implementation of a complete Enterprise Active Directory environment using Windows Server 2022 and VMware Workstation.

The objective of this lab was to simulate real-world Windows Server administration tasks performed by Windows Administrators, System Administrators, and IT Infrastructure Engineers.

The project covers the complete lifecycle of Active Directory deployment, including:

- Active Directory Domain Services (AD DS)
- Organizational Units (OU)
- User & Group Management
- DNS Configuration
- DHCP Configuration
- Group Policy Management
- Windows Client Domain Join
- File Server Configuration
- NTFS Permissions
- Home Folder Mapping
- PowerShell Administration
- Enterprise Troubleshooting

- ## 📑 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Project Objectives](#-project-objectives)
- [🛠️ Technologies Used](#️-technologies-used)
- [🏗️ Lab Architecture](#️-lab-architecture)
- [🚀 Features Implemented](#-features-implemented)
- [📅 10-Day Learning Journey](#-10-day-learning-journey)
- [📂 Repository Structure](#-repository-structure)
- [📸 Screenshots](#-screenshots)
- [💻 PowerShell Commands](#-powershell-commands)
- [🎤 Interview Preparation](#-interview-preparation)
- [📚 Learning Outcomes](#-learning-outcomes)
- [👩‍💻 Author](#-author)

---
## 🎯 Project Objectives

- Deploy Windows Server 2022 as a Domain Controller.
- Configure Active Directory Domain Services (AD DS).
- Create and manage Organizational Units (OUs).
- Manage users, groups, and security permissions.
- Configure DNS and DHCP services.
- Implement Group Policy Objects (GPOs).
- Join Windows 10 clients to the domain.
- Configure File Server with NTFS permissions.
- Configure Home Folder mapping.
- Perform Windows administration using PowerShell.
- Simulate real-world enterprise support scenarios.
- Build a professional GitHub portfolio for interview preparation.

---
## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Windows Server 2022 | Domain Controller |
| Windows 10 | Domain Client |
| VMware Workstation Pro | Virtualization Platform |
| Active Directory Domain Services | Identity Management |
| DNS | Name Resolution |
| DHCP | Automatic IP Address Assignment |
| Group Policy | Centralized Policy Management |
| SMB File Sharing | Shared Folder Management |
| NTFS Permissions | File Security |
| PowerShell | Windows Administration & Automation |

---
## 🚀 Features Implemented

✅ Installed and configured Windows Server 2022

✅ Promoted the server to a Domain Controller

✅ Created an Active Directory Domain

✅ Configured Organizational Units (OUs)

✅ Created and managed users and security groups

✅ Configured DNS

✅ Configured DHCP

✅ Joined Windows 10 client to the domain

✅ Configured File Server

✅ Applied NTFS permissions

✅ Configured Home Folder mapping

✅ Managed users with PowerShell

✅ Simulated enterprise support scenarios

✅ Performed Active Directory troubleshooting

---
## 🏗️ Lab Architecture
For the complete architecture diagram, see:

📁 **[Architecture/Architecture-Diagram.md](Architecture/Architecture-Diagram.md)**

The lab environment consists of one Windows Server acting as the Domain Controller and one Windows 10 client joined to the Active Directory domain.

```text
                    VMware Workstation
     -------------------------------------------------

             Windows Server 2022 (DC01)
          --------------------------------
          • Active Directory Domain Services
          • DNS Server
          • DHCP Server
          • Group Policy
          • File Server
          • Home Folder Mapping

                       │
                       │
                 Domain Network
                       │
                       ▼

             Windows 10 Client
          -------------------------
          • Domain Joined
          • Domain User Login
          • Shared Folder Access
          • Home Folder Access
```

---
## 📅 10-Day Learning Journey

| Day | Topic |
|------|-------|
| Day 1 | Windows Server 2022 Installation |
| Day 2 | Active Directory Users and Groups |
| Day 3 | Group Policy Management |
| Day 4 | DNS Configuration |
| Day 5 | DHCP Configuration |
| Day 6 | Domain Join and Client Management |
| Day 7 | File Server and NTFS Permissions |
| Day 8 | Shared Folders and Access Control |
| Day 9 | Active Directory Administration and PowerShell |
| Day 10 | Enterprise Administration and Lab Validation |

---
## 📂 Repository Structure

```text
Active-Directory-Lab
│
├── 01-Windows-Server-Installation
├── 02-Active-Directory-Users-and-Groups
├── 03-Group-Policy-Management
├── 04-DNS-Configuration
├── 05-DHCP-Configuration
├── 06-Domain-Join-and-Client-Management
├── 07-File-Server-and-NTFS-Permissions
├── 08-Shared-Folders-and-Access-Control
├── 09-Active-Directory-Administration-and-Backup
├── 10-Lab-Validation-and-Project-Completion
│
├── Architecture
├── Diagrams
├── Interview-Questions
├── PowerShell
└── Screenshots
```

---
## 📸 Project Screenshots

The following screenshots demonstrate the implementation of the Active Directory Lab.

| Component | Status |
|-----------|--------|
| Windows Server Installation | ✅ |
| Active Directory Domain Services | ✅ |
| Organizational Units (OU) | ✅ |
| Users and Groups | ✅ |
| DNS Configuration | ✅ |
| DHCP Configuration | ✅ |
| Group Policy Objects (GPO) | ✅ |
| Windows 10 Domain Join | ✅ |
| File Server | ✅ |
| NTFS Permissions | ✅ |
| Home Folder Mapping | ✅ |
| PowerShell Commands | ✅ |

> 📁 Detailed screenshots are available inside the **Screenshots** folder.
> ## 📸 Screenshots

View the complete implementation screenshots here:

➡️ **[Screenshots Gallery](Screenshots/README.md)**

---
## 💻 PowerShell Commands

The following PowerShell commands were practiced during this project:

| Command | Purpose |
|---------|---------|
| Get-ADUser -Filter * | List all Active Directory users |
| Get-ADUser -Filter * \| Select Name | Display only usernames |
| Export-Csv | Export Active Directory users to CSV |
| Get-Command Get-ADUser | Verify Active Directory module |

Additional PowerShell commands will be added as the project expands.

---
## 🎤 Interview Preparation

This project was also used as hands-on preparation for Windows Administrator and Infrastructure Support interviews.

Topics covered include:

- Active Directory
- Organizational Units
- User Management
- Group Policy
- DNS
- DHCP
- File Server
- NTFS Permissions
- Home Folder
- PowerShell
- Windows Troubleshooting
- Real-world Administration Scenarios

---
## 🎤 Interview Preparation

This project was also used as hands-on preparation for Windows Administrator and Infrastructure Support interviews.

Topics covered include:

- Active Directory
- Organizational Units
- User Management
- Group Policy
- DNS
- DHCP
- File Server
- NTFS Permissions
- Home Folder
- PowerShell
- Windows Troubleshooting
- Real-world Administration Scenarios

---
## 📚 Learning Outcomes

After completing this project, I gained hands-on experience in:

- Deploying Windows Server 2022
- Building an Active Directory environment
- Managing enterprise users and groups
- Configuring DNS and DHCP
- Implementing Group Policy
- Configuring File Servers
- Applying NTFS Permissions
- Managing Home Folder Mapping
- Performing PowerShell administration
- Troubleshooting enterprise Windows environments

---
## 👩‍💻 Author

**Payal Acharya**

Infrastructure & Windows Administration Enthusiast

This project was built as part of my hands-on learning journey in Windows Server Administration, Active Directory, and IT Infrastructure.

If you found this project helpful, feel free to ⭐ the repository.


Throughout the lab, multiple real-world administrative scenarios such as password resets, employee onboarding, employee offboarding, department transfers, file sharing, access control, and troubleshooting were successfully completed.

---
