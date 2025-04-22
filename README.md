# OPS210-FileShare-DHCP-PowerShell
Windows Server lab assignment covering file sharing, printer configuration, DHCP setup, and PowerShell automation. Completed as part of OPS210 at Seneca Polytechnic.
# Windows Server File Sharing, DHCP, and PowerShell Automation – OPS210 Lab

**Course:** OPS210 – Administration of Microsoft Systems  
**Date:** January 2024  
**Institution:** Seneca Polytechnic

---

## 🧠 Overview
This project covers a Windows Server practical assignment involving shared folder permissions, printer configuration, DHCP management, and PowerShell scripting. The goal was to simulate enterprise IT administration tasks in a domain-controlled environment.

---

## 🛠️ Key Tasks
- Created a new OU and security groups within Active Directory
- Assigned a user to a domain local group and applied NTFS permissions to a shared folder
- Set up a Canon shared printer using a TCP/IP port and adjusted its print security
- Configured DHCP with IP scope, subnet mask, gateway, DNS, and MAC-based reservations
- Developed a PowerShell script to:
  - Check for or create a `Reports` directory
  - Generate a log (`Practical2Report.log`) showing all installed printers
  - Include server name, current user, and timestamp
  - Display console confirmation of successful report creation

---

## 🔐 Permissions & Security
- Applied specific NTFS read permissions to file resources
- Restricted printer management to assigned groups
- Set appropriate DHCP configurations to control IP distribution
- Used PowerShell to automate report generation and directory validation

---

## 🧠 Skills Demonstrated
- Windows Server Administration  
- File Sharing & NTFS Permissions  
- DHCP Configuration & Address Reservation  
- Printer Management  
- PowerShell Scripting  
- Active Directory Group Management  
- IT Automation Practices  

---

## 📂 Notes
Screenshots were not retained for this submission. However, all configurations and scripting tasks were executed successfully, and validated via in-VM testing and the professor-provided rubric.

---

## ✅ Project Status
- ✔️ Completed and submitted
- ✔️ PowerShell script created and validated
- ✔️ DHCP and file/print services configured and tested
