<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

 - Step 1 Made new users in Active Directory, set their passwords, and added them to the right groups.
 - Step 2 Reset passwords and disabled accounts when needed.
- Step 3 Made Group Policy to set desktop wallpapers, force password rules, and block Control Panel.
- Step 4 Applied the policies to users and checked that they worked on client PCs 
<h2>Deployment and Configuration Steps</h2>

<p>
<img width="2622" height="1008" alt="image" src="https://github.com/user-attachments/assets/d09d4ff3-2deb-4239-a85f-ba8ca5b6b0a5" />
</p>
<p>
Created a new user in Active Directory and set up their account and Resetting a password in ADUC.
<br />

<p>
<img width="2638" height="1058" alt="image" src="https://github.com/user-attachments/assets/b0556d88-2430-4ea0-8c9d-b7460f1a2dc4" />
</p>This is where you edit policies that control security and user/computer behavior across the domain.
<p>

</p>
<br />

<p><img width="702" height="960" alt="image" src="https://github.com/user-attachments/assets/100fce9d-0c25-40e5-a463-47b9e06177a7" />

</p> By clicking the "Unlock account" box, the admin is manually unlocking the account so the user can log in again right away — without waiting for the system to unlock it automatically.
<p>
</p>
<br />
