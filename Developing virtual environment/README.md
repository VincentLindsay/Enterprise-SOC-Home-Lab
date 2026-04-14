# Overview
This section will entail the setup of a virtual network, as well as the respective virtual machines for each of the tools.

# Table of Contents
- [Creating the VNet]
- [Booting up Windows Machines]
- [Booting up Ubuntu Machines (SIEM, & SOC Workstation]


# Creating the VNET
* Since I am using VMware for this lab, I created a separate VNet using VMware's Virtual Network Editor.
* Similar to the Malware Analysis [lab](https://github.com/VincentLindsay/Malware-Analysis-Environment), I made a VNet that is completely separate to segment the network.
<img width="675" height="21" alt="image" src="https://github.com/user-attachments/assets/9fa7334b-a6cf-445e-adaf-6eacff4b0442" />

* This VNet mimics what an enterprise network would look like, and all respective VMs will be assigned static IP addresses.

# Booting up Windows Machines
* For the Active Directory Domain Controller server, I utilized Windows Server 2022 from the Microsoft evaluation center.
* Once downloaded, I bagan the installation.
* Most importantly, I chose the Windows server 2022 desktop environment
<img width="633" height="475" alt="image" src="https://github.com/user-attachments/assets/6552f671-7a24-4897-807b-6477e75c9c9d" />

<img width="1026" height="762" alt="image" src="https://github.com/user-attachments/assets/b6da75db-6a2b-45d8-ad9c-9befe491df94" />

* I was able to install, and configure the Server.

* For the Windows 10 Workstation, I performed the same actions within my Attack and Defend [lab](https://github.com/VincentLindsay/Security-Analysis-Projects/tree/main/Attack%20%26%20Defend%20lab#Configuring-the-Windows-machine)
* I Set up the VM as a Workstation that will be added to the domain later.

* *** add something to show installation of workstation ****

# Booting up Ubuntu Machines (SIEM, & SOC Workstation)
* For the SOC Workstation, I chose Ubuntu client since most of the SIEM, and security tools will utilize GUI web applications to navigate the consoles.
* I obtained the ISO from the downloads page for Ubuntu desktop.
  **** add screenshot of homescreen to show installation ***
* I will also add the Ubuntu desktop workstation to the domain later as well.

* For the SIEM (Kibana) server, I utilized Ubuntu Server version 24.04.4 LTS
