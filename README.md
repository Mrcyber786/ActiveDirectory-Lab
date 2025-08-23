# Active Directory Home Lab (VirtualBox)

This project demonstrates how I set up a Windows Server 2019 environment in VirtualBox to configure **Active Directory Domain Services (AD DS)**, networking services, and domain management.  

The goal of this lab was to practice deploying a domain controller, creating administrative accounts, and configuring core services like DHCP and NAT that are commonly found in enterprise environments.

---

## Project Overview
- **Platform:** Oracle VirtualBox  
- **Server OS:** Windows Server 2019 (Domain Controller)  
- **Services Configured:**  
  - Active Directory Domain Services (AD DS)  
  - DHCP  
  - Routing and Remote Access Service (RRAS) with NAT  
- **Key Skills Demonstrated:**  
  - Server installation and configuration  
  - Network setup (static IPs, NAT)  
  - Domain administration  
  - User/Group management  

---

## Steps and Screenshots

### Step 1: Windows Server Setup
I installed Windows Server 2019 in VirtualBox and completed the initial configuration to prepare the server as a Domain Controller.  

![Windows Server Setup](Screenshots/01.png)  
![Windows Server Setup](Screenshots/02.png)  
![Windows Server Setup](Screenshots/03.png)  

---

### Step 2: Configure Static IP for Domain Controller
A Domain Controller requires a static IP address to ensure network stability and proper DNS resolution.  
I configured the IPv4 settings on the server.  

![Configure Static IP](Screenshots/04.png)  

---

### Step 3: Install Active Directory Domain Services (AD DS)
Using **Server Manager → Add Roles and Features**, I installed the Active Directory Domain Services role to enable domain management.  

![Install AD DS](Screenshots/05.png)  
![Install AD DS](Screenshots/06.png)  
![Install AD DS](Screenshots/07.png)  
![Install AD DS](Screenshots/08.png)  

---

### Step 4: Create a Domain Administrator Account
After setting up AD DS, I created a new **domain administrator account** inside Active Directory Users and Computers (ADUC).  
This account was added to the **Domain Admins** group for management tasks.  

![Create Admin Account](Screenshots/09.png)  
![Create Admin Account](Screenshots/10.png)  

---

### Step 5: Install Routing and Remote Access with NAT
To provide internet access to the domain, I installed **Routing and Remote Access (RRAS)** and configured **Network Address Translation (NAT)**.  

![Install RRAS](Screenshots/11.png)  
![Install NAT](Screenshots/12.png)  

---

### Step 6: Configure DHCP Server
Finally, I installed the **DHCP Server role** and created a DHCP scope to automatically assign IP addresses to domain clients.  

![Install DHCP](Screenshots/13.png)  
![Configure DHCP Scope](Screenshots/14.png)  

---

## Conclusion
This lab gave me practical experience in building an enterprise-style Windows Server environment in a virtualized lab. I practiced:  
- Installing and configuring Windows Server  
- Deploying Active Directory Domain Services  
- Managing domain users and permissions  
- Setting up networking with NAT and DHCP  

These are the same core skills IT administrators use to manage real-world Windows Server environments.

---
