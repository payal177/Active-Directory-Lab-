# 🏗️ Enterprise Active Directory Lab Architecture

```mermaid
flowchart TB

    VM["🖥️ VMware Workstation"]

    DC["Windows Server 2022

DC01.payal.local

Domain Controller"]

    AD["Active Directory<br/>Domain Services"]

    DNS["DNS Server"]

    DHCP["DHCP Server"]

    GPO["Group Policy"]

    FS["File Server

CompanyData"]

    HF["Home Folder

H:\ Drive Mapping"]

    CLIENT["Windows 10 Enterprise Client"]

    USER["Domain Users

• Rahul Sharma
• Aarav Sharma"]

    VM --> DC

    DC --> AD
    DC --> DNS
    DC --> DHCP
    DC --> GPO
    DC --> FS
    DC --> HF

    DC --> CLIENT

    CLIENT --> USER

    USER --> FS

    USER --> HF
```
