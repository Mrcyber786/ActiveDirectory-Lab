# Active Directory Home Lab Project

This project demonstrates the setup and configuration of a Windows Server 2019 Active Directory lab environment using VirtualBox.  
The lab includes configuring a Domain Controller (DC), Active Directory Domain Services (AD DS), DHCP, and Routing/NAT.  

 All screenshots documenting the setup process are included in the **Screenshots** folder of this repository.  

---

## Project Overview

The purpose of this lab is to showcase practical hands-on experience with:
- Installing and configuring Windows Server 2019 in VirtualBox  
- Setting up a Domain Controller with AD DS  
- Creating and managing domain administrator accounts  
- Configuring network services such as DHCP and NAT  
- Preparing a functional environment that simulates enterprise IT infrastructure  

---

## Steps Completed

### 1. VirtualBox Setup
- Installed and configured a new Virtual Machine in **VirtualBox**.  
- Allocated resources (RAM, CPU, disk space) for the Windows Server.  
- Configured networking for the VM to support domain and client communication.  

---

### 2. Windows Server Installation
- Installed **Windows Server 2019** on the VirtualBox VM.  
- Performed the initial setup, including administrator password configuration and updates.  

---

### 3. Configure Static IP for Domain Controller
- Assigned a **static IP address** to the Domain Controller to ensure reliable communication within the network.  
- Configured DNS to point to the DC itself.  

---

### 4. Install Active Directory Domain Services (AD DS)
- Used the **Add Roles and Features Wizard** to install AD DS.  
- Promoted the server to a **Domain Controller**.  
- Created a new forest and root domain for the lab environment.  

---

### 5. Create Domain Admin Account
- Added a new **administrator account** within Active Directory Users and Computers (ADUC).  
- Verified domain authentication by logging in with the new account.  

---

### 6. Install Routing and Remote Access (RRAS) with NAT
- Installed **Routing and Remote Access Services** through Server Manager.  
- Configured **Network Address Translation (NAT)** to allow client VMs to access the internet via the Domain Controller.  

---

### 7. Configure DHCP Server
- Installed the **DHCP role** on the Domain Controller.  
- Created and configured a **DHCP scope** to dynamically assign IP addresses to client machines.  
- Authorized the DHCP server in AD DS.  

---

## Conclusion

This lab project demonstrates a full setup of a small-scale enterprise IT environment, including:  
- Active Directory Domain Services (AD DS)  
- Domain administration  
- DHCP and NAT services  
- VirtualBox-based virtualization  

The project highlights practical system administration skills applicable to real-world IT and cybersecurity roles.  

---

## Repository Contents
- **README.md** → Project documentation (this file)  
- **Screenshots/** → Folder containing step-by-step screenshots of the setup process  

---
