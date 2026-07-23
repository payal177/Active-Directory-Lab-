# ⚡ PowerShell Commands for Active Directory

This document contains the PowerShell commands used during the Enterprise Active Directory Lab.

These commands helped automate common Active Directory administration tasks and are frequently used by Windows Administrators.

---

# 📋 Commands Practiced

| Command | Purpose |
|---------|---------|
| `Get-ADUser -Filter *` | Display all Active Directory users |
| `Get-ADUser -Filter * \| Select Name` | Display only usernames |
| `Get-ADUser -Identity "Rahul Sharma"` | Display a specific user |
| `Get-Command Get-ADUser` | Verify the Active Directory module |
| `Export-Csv` | Export Active Directory users to a CSV file |

---

# 💻 Example Commands

## List all Active Directory users

```powershell
Get-ADUser -Filter *
```

---

## Display only usernames

```powershell
Get-ADUser -Filter * | Select Name
```

---

## Export users to CSV

```powershell
Get-ADUser -Filter * | Select Name | Export-Csv C:\Users.csv -NoTypeInformation
```

---

## Verify Active Directory Module

```powershell
Get-Command Get-ADUser
```

---

# 🌟 Skills Demonstrated

- Active Directory Administration
- PowerShell Basics
- User Enumeration
- CSV Export
- Windows Server Automation

---

⭐ These commands represent the PowerShell operations performed during the Active Directory Lab.
