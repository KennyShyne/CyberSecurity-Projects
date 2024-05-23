# CyberSecurity-Projects 

This is my attack and defense home lab environment where i will practice both Red and Blue teaming. I have started this project to sharpen my cybersecurity skills and become a better security engineer.
<h2>Below is the list of my courses i'm taking for my Security Engineering Journey:</h2>
 
 **Blue Teaming:**
- Windows Digital Forensics by TCM Academy
- Malware Analysis and triage by TCM Academy
- Blue Team Junior Analyst By Security Blue Team
- Lets Defend
 

 **Red Teaming:**
- Ethical Hacking by TCM Academy
- Web Application Security by TCM Academy

<h2>Lab Diagram & Description</h2>
<p align="center">
<img src="https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/806182cf-f79b-4107-a31a-28ffb68df47a)"/>

- Virtualization Software - VMware Workstation 17
- PFsense - Firewall
- Splunk - SIEM
- Kali Linux - Attacking Machine
- Victim Environment Windows Server (Domain) - Windows, Linux and Mobile OS boxes
- Malware Analysis, Digital Forensics & Incident Response Environment 
<h2>

<h2>Lab Setup</h2>
# Table of Contents

<!-- MarkdownTOC lowercase_only_ascii="true" depth=3 autolink="true" bracket="round" -->

- [PFsense Setup](#pfsense-setup)

- [Kali Linux Setup](#kali-linux-attacking-machine-setup)
 - [PFsense Web Config](#pfsense-web-config)

- [Windows Domain Controller Setup](#windows-domain-controller-setup)
 - [Adding Workstations to the Domain](#adding-workstations-to-the-domain)

- [Splunk Installation & Setup](#splunk-installation-and-setup)
 - [Splunk Universal Fowarders Setup](#splunk-universal-fowarders-setup)
 

$~$
### PFsense Setup
<p align="center">

**- Below is the site i downloaded the Pfsense ISO**
![2024-04-15 21_58_36-y2mate com - Cybersecurity Detection Lab Configuring Pfsense Firewall Network Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/460c3e46-84af-4398-8278-cd256cf6e260)
 
**- VMware setup and installation**
  
![2024-04-15 22_31_13-Create Virtual Machine](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/4f2023a9-2942-425b-8168-1c510edd015c)

![2024-04-16 22_10_21-Hardware](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/540b20cb-1d08-4e4e-bb68-6de51dd179d3)

![2024-04-16 21_53_20-Pfsense Firewall  Running  - Oracle VM VirtualBox](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3a96a074-4cf0-43c2-86f6-0613b7792641)

![2024-04-16 22_18_29-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/176c6363-e090-4cfc-9fb5-544e0f41ed90)

**- Activating Network Interfaces/Ports**

![2024-04-16 22_23_47-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/156f6956-ba0e-4033-9661-29da4053022f)

**- Assigning IP Addresses to my interfaces**

![2024-04-16 22_41_07-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/efadfac7-5050-41b2-ada9-9a3498ad08b6)

![2024-04-16 23_01_50-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f6541ee5-1e55-4c29-8111-2d0e166ee719)

$~$
### Kali Linux Attacking Machine Setup

**- Site i downloaded my ISO**
![Screenshot (2)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/9701535c-5f4d-40fc-89bd-ceb2039e39b5)

**- VMware setup and installation**

![Screenshot (3)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/338c9bb9-0e96-4897-a0ce-874629ecce0b)

![Screenshot (4)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/ef2dc980-e32e-4a57-a090-a3457de61cd1)

**- My login screen (I have already changed my default username and password)**
![Screenshot (5)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e0f02c45-06b0-4e06-b1c8-e328b986a081)

$~$

### PFsense Web Config 

**Using kali workstation**
![2024-05-18 09_43_30-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/7e29d61c-fa0d-4d2a-8b24-7e5fc9c470e1)

![2024-05-18 09_57_56-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/a48e2dfa-c0b8-46cb-9242-f413533786b5)

![2024-05-18 09_57_08-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f9579629-f1a5-414d-909c-bcf544690397)

![2024-05-18 10_12_16-Window](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/5ff5cce9-0ca7-4f7d-8e85-88d1e5421984)

![2024-05-18 10_14_08-Window](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/92b6cb15-1ddb-4366-b138-510d6f882778)

![2024-05-18 10_14_59-Window](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/c8f1d7f2-3eb9-4a05-812f-d9d07827d61a)

![2024-05-18 10_15_44-Window](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/11a2226b-4a67-450a-9c0f-d1d0fa8349a7)

![2024-05-18 10_16_58-Window](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/6532ed79-9916-41cd-b728-142f0f05ee22)

$~$
**- Interface Configurations and renaming**
![2024-05-18 10_26_09-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1af9c7c8-fca5-4bb8-a01f-d8d116eb0692)

![2024-05-18 10_35_15-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/01b0ee81-5ef8-4868-bd11-cfc83330d4a6)

$~$
**- Bridge Configurations**
![2024-05-18 10_39_36-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/303d1775-b508-4677-9e89-a191a3800efd)

![2024-05-18 10_40_23-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/75a01fc0-ca80-46cf-a6d7-ba1ab49849f9)

$~$
**- Firewall Configurations**
![2024-05-18 10_42_19-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/d7648531-740f-40b2-a31e-6df922ed25ac)

![2024-05-18 10_43_36-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/ffe321d4-d66b-4af3-8bd2-0258496364a2)


$~$
### Windows Domain Controller Setup
**- I will be using Windows Server 2019 as my Domain Controller. Installation and setup below**
![2024-05-22 19_44_16-Windows Server 2012 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/053e1e63-8a2b-435e-baf2-14aa66cce08c)
![2024-05-22 20_06_52-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e0d4c347-3302-4fd8-8855-21d21a6b8279)
![2024-05-22 20_07_35-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/9ddf12e1-4059-4deb-a22e-ec3beb28e625)
![2024-05-22 20_07_47-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/61c8ef51-c89d-4391-86ba-e5af531bee98)
![2024-05-22 20_08_07-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/a2d917f1-74a2-4cdd-869c-625a4112ecaf)

**- Configuring Roles and Features**
![2024-05-22 20_11_25-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/7fbde18d-11fc-48a2-be8c-1f2950c434ea)
![2024-05-23 20_11_52-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/895da805-ffab-45ec-97ad-f2559452c90c)
![2024-05-23_1 20_12_09-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/38e4163e-9d63-403c-a4c2-e47582010dd9)
![2024-05-22 20_12_49-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1c9fe261-a94d-4c5d-8fc0-0b445d3881e0)
![2024-05-22 20_13_29-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/58a79823-d84a-42b8-9250-cf6a099b378e)
![2024-05-22 20_14_40-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/13d31ec4-bb27-4f38-bed1-9646495a7cbc)
![2024-05-22 20_15_39-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/5198f590-e733-4e32-859d-df6806158698)

$~$
**- Promoting the domain controller**
![2024-05-22 20_16_37-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/389d1a3e-2828-448b-b03c-2e5548b8e532)

![2024-05-22 20_17_08-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e917cdd2-2f12-4fc9-b362-93fb187d31c7)
![2024-05-22 20_17_39-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/22bf23f9-231c-49e7-8f6c-779f4b62e160)
![2024-05-22 20_18_03-y2mate com - Cybersecurity Detection Lab Building An Active Directory Lab for Se](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/a85d2a7d-3b9f-44f5-9068-c367408fea22)


### Adding Workstations to the Domain

$~$
### Splunk Installation and Setup
### Splunk Universal Fowarders Setup
