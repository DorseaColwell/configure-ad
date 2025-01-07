<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Provision Virtual Machines

Create a Windows Server VM to act as the domain controller and a Windows 10 VM as a client machine in Azure.
- Install and Configure Active Directory

Install the Active Directory Domain Services (AD DS) role on the Windows Server VM and promote it to a domain controller.
- Join Client Machine to the Domain

Configure the Windows 10 VM to join the newly created Active Directory domain.
- Create Users and Groups

Set up user accounts and organize them into groups within Active Directory for resource management and security.


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Provision Azure Virtual Machines

Set up two VMs: one with Windows Server 2022 and another with Windows 10 (21H2).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Active Directory Domain Services (AD DS)

On the Windows Server VM, install the AD DS role to promote it to a domain controller.
Configure the Domain and Join the Client Machine

Create a new domain within the AD DS and join the Windows 10 VM to this domain.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set Up Users and Groups

Within Active Directory, create user accounts and organize them into appropriate groups.
</p>
<br />
