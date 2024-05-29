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
![2024-05-25 10_54_00-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/beab39d3-da2a-43c6-aa57-cbc933584acd)
![2024-05-25 10_58_39-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/52174fba-56bb-4d49-919b-99e7eb1e6c27)
![2024-05-25 11_00_27-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/24ba580a-5139-4399-8ded-74fac7fb7745)
![2024-05-25 12_31_34-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/081ec174-aac5-4496-874f-0f3a64caed6b)


**- Configuring Roles and Features**
![2024-05-25 11_03_36-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3203d485-b3c7-4572-b83d-15c995a94270)
![2024-05-25 11_04_50-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/05f0872b-9344-473a-85f2-8fceeb8a6cf2)
![2024-05-25 11_05_29-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f69c3c3e-6074-4980-8d38-8891a286c636)
![2024-05-25 11_06_48-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/33d618ad-d065-4214-8d8f-03edce8c4de3)
![2024-05-25 11_07_39-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/781076f4-746e-49b2-a473-0ea9acd87254)
![2024-05-25 11_07_58-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1e58f95a-7308-43e4-89d1-62856634f083)
![2024-05-25 11_08_52-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/80b0003d-f31f-4354-b31a-4ef6d2bad517)
![2024-05-25 11_09_14-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b9cb68e2-14cf-484b-a937-710fa2781f56)
![2024-05-25 11_11_52-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/914c2d42-4dfc-43e5-b6f0-7d2ffb21506e)


$~$
**- Promoting to a Domain Controller**
![2024-05-25 11_18_04-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b30be317-3bf3-4c12-b885-6f114d26d554)
![2024-05-25 11_18_38-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/02701e1a-a945-4582-8a39-264a00dab57b)
![2024-05-25 11_19_06-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e1126990-71e1-44fb-b02e-0ca5935cab68)
![2024-05-25 11_20_55-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/5a3ced4e-7d14-4f21-ade3-6358e2e3c204)
![2024-05-25 11_22_44-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f5bee711-0486-4582-95fa-90f9e69967cf)
![2024-05-25 11_23_00-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/ed6d5e38-111c-4409-99e6-97a12459fc90)
![2024-05-25 11_23_45-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b5cd0053-660f-45f8-af9f-2e868815f46e)
![2024-05-25 11_24_01-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/dbec8b5e-8590-4c2a-a931-f8496de62f3a)
![2024-05-25 11_37_13-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/9e43ded2-46a2-4111-841e-9e4578f8e27c)
![2024-05-25 11_40_13-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/c033dd3a-85ea-4fa4-a832-f8f445511b84)


$~$
**- Active Directory Services Config**
![2024-05-25 11_40_43-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/39570259-f3d0-4fd6-a540-2936789283f8)
![2024-05-25 11_41_41-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/5bac6602-1430-40fd-8cc3-03b10c7c56de)
![2024-05-25 11_43_37-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b30bef5d-01fb-4914-b9a9-f89f87a2aa5e)
![2024-05-25 11_44_18-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/58c1a31b-6fe2-4c93-9f05-672b314139bc)
![2024-05-25 11_44_33-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/9d5411b7-720b-4d66-b247-062d046af96b)
![2024-05-25 11_45_03-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/2017a460-d7a0-4b50-9e08-a1c8903510a8)
![2024-05-25 11_48_37-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/28543a59-76f0-4877-8331-f1283066d3a9)


$~$
**- Active Directory Certificate Services Config**
![2024-05-25 11_47_56-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/80195cae-2218-42e1-bd65-00dc394ddffa)
![2024-05-25 11_55_17-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/ab913a6f-7768-4db9-a79e-d2c120f69a1e)
![2024-05-25 11_57_38-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e3b53b5d-81b4-4356-92e1-0eded1a3603c)
![2024-05-25 11_58_17-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/cce35ac9-ca3f-4e16-91c2-1b4022ec5e1c)
![2024-05-25 11_59_07-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/71e5592d-6529-4f56-8094-d6797e460977)
![2024-05-25 11_59_29-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1f707f7a-0047-4a60-ac03-ad0909e73ef3)
![2024-05-25 11_59_45-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/aeafd92b-9d13-42e8-90d5-409c49c35f3a)
![2024-05-25 12_00_02-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/5948873c-2da9-4931-9bf9-d21efd34f0e2)
![2024-05-25 12_00_34-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/734f9844-a2df-4880-a022-5abbb774af1e)
![2024-05-25 12_00_49-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1462d77d-b346-4808-a7ca-d30e5b72811c)
![2024-05-25 12_01_04-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/39fab27e-aebe-47fd-8afb-24f918f4f48e)
![2024-05-25 12_01_18-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/57eb7ed1-4d8c-40d1-be5c-4af07a97cfd3)
![2024-05-25 12_10_58-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/81d5a2bc-7cf8-448b-9c87-979cc71eb8f2)

### Adding Users to the Domain
![2024-05-25 12_12_02-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/49030865-886f-4e92-8716-558487041a07)
![2024-05-25 12_12_51-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/59431cb7-9944-427c-b994-3c952318e7be)
![2024-05-25 12_14_11-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3051c6dd-6c16-44e5-9053-f9c27f3bafcb)
![2024-05-25 12_17_12-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/d0d9ac2a-1a62-4ea7-912b-c088a80a63e7)
![2024-05-25 12_19_31-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/afaaac5f-5202-4073-b870-6f58e9116c03)

### Adding Workstations to the Domain
Our windows PC should be in the same subnet as our Domain Controller
![2024-05-25 15_41_03-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/053e8701-93a7-4816-99f1-17e9f3055ed7)
![2024-05-25 15_44_26-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/d7f44462-0962-4438-9860-df4c41964454)
![2024-05-25 15_45_06-Windows 10 x64 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/59b966c3-996e-489b-973a-f477eeeed9bd)
![2024-05-25 15_46_16-Windows 10 x64 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b16b45c8-8d38-475b-b36c-0c6166618853)
![2024-05-25 15_46_45-Windows 10 x64 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/58baab8b-da0a-43db-96f3-4b9771cab350)
![2024-05-25 15_47_09-Windows 10 x64 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/4fad210f-17de-45fe-9d0e-c19b3c20197f)
![2024-05-25 15_49_16-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f3b0bb26-95a3-45bf-bef1-f52ece95cb03)
![2024-05-25 15_52_08-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1701f5ba-0436-4d1f-bed9-793f2037a4a9)


**- Configuring Domain Controller As Victim Network on Pfsense firewall**
![2024-05-25 13_07_16-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/a8ffb836-9591-4e8a-9e0b-39670326d787)
![2024-05-25 13_09_29-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/ea8c226a-b2bb-4ea6-9058-f22d97a59c74)
![2024-05-25 13_12_15-Kali SK 2024 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/a33f6a12-5d8c-4254-8c75-394d1f2e59b5)

$~$
### Splunk Installation and Setup
**- Ubuntu Server Installation and Setup**
![2024-05-25 16_03_21-Virtual Machine Settings](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/0a2eb0bf-5c60-4f8c-beff-d0d3562fc142)
![2024-05-25 16_06_57-Ubuntu Splunk Server - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/e102056c-6459-4e82-8598-a2b669c9b1b5)
![2024-05-25 16_07_23-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/aa5ce4cf-fbc3-45c1-958d-e0c2a8121104)
![2024-05-25 16_09_48-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/17b72243-bad1-4de1-b3a5-e8bb0719dc25)
![2024-05-25 16_10_09-Ubuntu Splunk Server - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/4561df5c-ff52-482a-a111-4193e3b8b144)
![2024-05-25 17_21_29-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/71de0101-5636-4d3f-8cb8-46ec5a265752)
![2024-05-25 17_28_16-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/48845b46-1af1-41db-9288-3b188c3052a4)
![2024-05-25 17_33_49-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/fee79b40-16e9-4d81-a379-872f3219eb48)
![2024-05-25 17_33_49-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/b0a1794c-3443-429e-9ca1-da1d2113b11f)

**- Ubuntu Tasksel Installation**
![2024-05-25 17_37_19-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/c556de6e-f35e-4834-9f47-486c2d1f2e4a)
![2024-05-25 17_41_47-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f8c19442-0d27-4fc1-be24-036c6a96acb0)
![2024-05-25 19_14_41-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/db6b7baf-559b-4301-9f5c-d1266d4060e4)

**- Splunk Installation and Setup**
![2024-05-26 11_04_57-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/fa963aee-35ba-4fc8-a23a-cc1461102e53)
![2024-05-26 11_05_34-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/4426c67e-0841-486f-90bf-33b5f40f3a8a)
![2024-05-26 11_07_25-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/0d9219cd-f663-4837-a3bd-a4b90a40660e)
![2024-05-26 11_09_38-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/eff556c4-ada7-42ed-a298-a84a486784ef)
![2024-05-26 11_11_58-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/481d9b29-15bd-420d-8afb-61d182a9f169)
![2024-05-26 11_14_43-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/36fa1758-fa1a-4cf7-8bc2-e236a439c305)
![2024-05-26 11_17_34-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/dbd03d2e-d884-4301-87b8-14ce61439ae7)
![2024-05-26 11_21_14-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3758b03f-72b2-48ef-8024-4a2ad9100357)
![2024-05-26 11_23_57-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/18c9e80e-0cc5-4ed9-bbb6-e8e1b29a2d2d)
![2024-05-26 11_28_22-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/15620539-ed42-4a8b-960b-47f3845059c7)
![2024-05-26 11_32_54-y2mate com - Cybersecurity Detection Lab Forwarding Windows Event Logs to Splunk](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/232fc36d-6079-404d-b70a-38cf23ef2d7b)
![2024-05-26 11_43_41-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3716eea7-3b0b-46af-a0e0-b005539aa91d)
![2024-05-26 11_45_22-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/6c7415c2-10be-43e9-acf5-72d0152c5409)
![2024-05-26 11_48_05-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/dc21731c-3585-4811-aeb7-44059426972d)
![2024-05-26 11_49_18-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/6f2e5652-30b3-421b-8791-e6ffa989b1ea)


### Splunk Universal Fowarders Setup
**- Setup on Domain Controller**
![2024-05-26 16_30_59-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/6dc673fc-d5ef-4c64-8e9a-9c89ecb1fd87)
![2024-05-28 19_57_52-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/7ac31456-add7-407b-9243-a891a2efcf84)
![2024-05-28 20_04_09-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/c4386977-62ca-46b9-b948-a83e1ee88dd4)
![2024-05-28 20_04_52-Windows Server 2019 - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/f8a2c85a-79be-4175-b6f6-636bddb7197f)

**- Setup on Splunk**
![2024-05-29 10_46_07-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/61858bcd-7fdf-44cd-91db-2286091ed718)
![2024-05-29 10_48_10-](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/2385e63c-5d90-4251-aa1a-1cb910e0944b)
![2024-05-29 10_49_13-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/1e0fbc8b-cfa2-42c0-85ce-8aed438294de)
![2024-05-29 11_03_02-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3e2ab240-37ff-4176-8e4c-ca0859a95905)
![2024-05-29 11_14_22-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/3010c124-faf8-44a6-8a22-1eabe105e56a)
![2024-05-29 11_15_55-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/7df9294d-9ba8-4cfe-9b5f-e583c5e20df8)
![2024-05-29 11_17_50-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/0b623ecc-7844-41be-8b60-f3bf0dd04c06)
![2024-05-29 11_20_13-Ubuntu Splunk - VMware Workstation 17 Player (Non-commercial use only)](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/67bc95fe-079b-4672-8e44-4ad9d04b5f2d)
![2024-05-29 12_06_36-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/274ab009-ef2c-40ae-b3ad-d26996f31b6f)
![2024-05-29 11_22_37-Greenshot](https://github.com/KennyShyne/CyberSecurity-Projects/assets/102590763/333b6b48-deab-42ca-a266-318bad32e79b)




