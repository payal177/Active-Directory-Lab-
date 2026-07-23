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

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-project-objectives)
- [Technologies Used](#-technologies-used)
- [Architecture](#-architecture)
- [Repository Structure](#-repository-structure)
- [Screenshots](#-project-screenshots)
- [PowerShell Commands](#-powershell)
- [Interview Questions](#-interview-questions)
- [Skills Demonstrated](#-skills-demonstrated)
- [Learning Outcomes](#-learning-outcomes)
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
## 📸 Project Screenshots


A complete implementation gallery is available below.

➡️ **[View Complete Screenshot Gallery](Screenshots/README.md)**

> 📁 Detailed screenshots are available inside the **Screenshots** folder.

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
## 🎤 Interview Readiness

This project helped me prepare for Windows Administrator and Infrastructure Support interviews by providing hands-on experience with:

- Active Directory Administration
- DNS & DHCP Troubleshooting
- Group Policy Management
- NTFS Permissions
- User Provisioning & Deprovisioning
- File Server Administration
- PowerShell Basics
- Enterprise Troubleshooting Scenarios

---
## 📚 Key Skills Gained

Throughout this project, I developed practical experience in:

- Windows Server Administration
- Enterprise Active Directory Deployment
- Identity & Access Management
- File Server Administration
- Infrastructure Troubleshooting
- Windows PowerShell Administration
- Technical Documentation
- IT Support Best Practices

---
## 👩‍💻 Author

**Payal Acharya**

Infrastructure & Windows Administration Enthusiast

This repository showcases my hands-on implementation of an Enterprise Active Directory environment using Windows Server 2022 and VMware Workstation.

It demonstrates practical skills in Windows Administration, Active Directory, DNS, DHCP, Group Policy, File Server Management, NTFS Permissions, PowerShell, and enterprise troubleshooting.
---

⭐ If you found this project useful, feel free to star the repository.

Built with ❤️ using Windows Server 2022 & VMware Workstation.
