# 🏗️ Enterprise Active Directory Lab Architecture

This document provides an overview of the architecture used to build the **Enterprise Active Directory Lab** using **Windows Server 2022**, **Windows 10**, and **VMware Workstation Pro**.

---

## 🎯 Objective

The lab was designed to simulate a real-world Windows Server environment and demonstrate:

- Active Directory Domain Services (AD DS)
- DNS & DHCP
- Group Policy
- File Server & NTFS Permissions
- Home Folder Mapping
- Windows PowerShell Administration

---

## 🖥️ Lab Components

| Component | Purpose |
|-----------|---------|
| Windows Server 2022 | Domain Controller (DC01) |
| Windows 10 | Domain Client |
| VMware Workstation Pro | Virtualization Platform |
| Active Directory | Identity Management |
| DNS & DHCP | Network Services |
| Group Policy | Centralized Administration |
| File Server | Shared Folder Management |

---

## 📸 Architecture Diagram

![Enterprise Lab Architecture](../Screenshots/12-Lab-Architecture.png)

---

## 🔄 Infrastructure Workflow

1. Windows 10 client joins the **payal.local** domain.
2. DHCP assigns an IP address.
3. DNS resolves the Domain Controller.
4. Active Directory authenticates users.
5. Group Policies are applied.
6. Users access shared folders and Home Folders based on permissions.

---

⭐ This architecture demonstrates the core components of an enterprise Windows infrastructure used by Windows Administrators and Infrastructure Engineers.
