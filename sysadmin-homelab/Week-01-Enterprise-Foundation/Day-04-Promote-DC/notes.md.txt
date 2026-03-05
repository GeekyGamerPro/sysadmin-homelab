# Day 4 — Promote DC01 to Domain Controller

- Active Directory Domain Services Configuration Wizard opened
- Deployment Configuration: Added new forest
  - Domain: **corp.geekytech.local**
- Domain Controller Options:
  - Forest & Domain functional level: Windows Server 2016 (lab limitation)
  - DNS Server checked
  - Global Catalog checked
  - RODC unchecked
  - DSRM password set
- DNS Options warning noted (normal in lab)
- NetBIOS domain name: **CORP**
- Paths left as default
- Review + Install summary confirmed
- Prerequisites check completed
- Installation / Promotion completed successfully
- DC01 rebooted and now active as **Domain Controller**
- Verification:
  - Local Server page shows DC01, domain, and roles
  - DNS Manager shows forward lookup zone `corp.geekytech.local`
  - Active Directory Users and Computers shows domain and default containers
- Screenshots captured:
  1. Deployment Configuration
  2. DC Options
  3. DNS Options
  4. NetBIOS Name
  5. Paths
  6. Prerequisites Check
  7. Installation Progress
  8. Local Server after promotion
  9. DNS Manager
  10. ADUC