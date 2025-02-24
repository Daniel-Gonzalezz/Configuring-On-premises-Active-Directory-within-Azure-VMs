<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Log into Azure Portal and Start VM Creation
- Step 2: Configure Basic Settings
- Step 3: Set Up Networking
- Step 4:  Review, Create, and Access VM
  

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/facec423-5635-4530-aa18-0e5396a0c7ce)
Step 1: Log into Azure Portal and Start VM Creation

Open your browser and go to https://portal.azure.com.

Sign in using your Microsoft Azure credentials.

Search for "Virtual Machines" in the top search bar and select "Virtual Machines" from the results.

Click the "+ Create" button and select "Azure virtual machine"




![image](https://github.com/user-attachments/assets/85145b03-cfb4-48e4-9307-e8529ce623b0)
Step 2: Configure Basic Settings

Select your Subscription and Resource Group.

Provide a unique Virtual Machine Name and choose your Region.

Select the OS Image (like Windows Server 2019 or Ubuntu 20.04).

Choose a Size based on CPU and RAM needs.


![image](https://github.com/user-attachments/assets/583843b0-29bb-4c17-8cff-b43ce0968c6a)

Step 3: Set Up Networking

Ensure a Virtual Network and Subnet are selected or created.

Configure Public IP if remote access is needed.

Select the appropriate Inbound Ports (like RDP for Windows or SSH for Linux).
