# Week 01 – Enterprise Foundation

## Day 1 – Lab Design

**Lab purpose:** Create first domain controller VM for sysadmin homelab.  
**VM Name:** DC01  
**OS:** Windows Server 2022 Standard (64-bit)  

### Hardware
- RAM: 4096 MB  
- CPUs: 2  
- Disk: 60 GB (dynamically allocated)  

### Network
- Adapter 1: NAT  
- Cable connected: ✅  

### Snapshot
- Name: Day1_PreInstall  
- Description: VM created with hardware and network configured  

### Lessons Learned
- Always plan resources before first boot  
- Snapshot before installing OS is critical  
- VirtualBox UI wording can be tricky (Pre-allocate = fixed size)