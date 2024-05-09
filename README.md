
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Configure Roles by selecting Admin Panel -> Agents -> Roles. Create a role named "Supreme Admin" that has all available permissions.
</p>
<p>
<img src="https://i.imgur.com/ju94z9h.png"/>
</p>
<br />

<p>
Configure Departments by selecting Admin Panel -> Agents -> Departments and create a department called "System Administrators".
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Configure Teams by selecting Admin Panel -> Agents -> Teams and add Level II Support.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Allow anyone to create tickets by selecting Admin Panel -> Settings -> User Settings and ensure that "Require registration and login to create tickets" is not selected.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Configure Agents by selecting Admin Panel -> Agents -> Add New and add two new agents named Jane and John.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Configure Users by selecting Agent Panel -> Users -> Add New and add two users, Karen and Ken.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Configure SLA by selecting Admin Panel -> Manage -> SLA and add: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours).
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Configure Help Topics by selecting Admin Panel -> Manage -> Help Topics and add the following: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
