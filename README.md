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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.gyazo.com/e70bee7ec5c64aebf5ec22536f16ce3d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/5f88fc8b9e21de6f7385df9a78d58d56.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I began by creating roles. Roles in osTicket define the permissions and access levels for agents. By setting up roles, I was able to control what agents can view, edit, or manage within the system. For example, I created a "Supreme Admin" role that can access everything.
</p>
<br />

<p>
<img src="https://i.gyazo.com/416f37d781ab37dc7d768b399e7d8a44.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/0bc938369dcbe319aae63897b5441ad1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I created a department. Departments are used to organize and route tickets based on their subject matter. For instance, I created a department called "SysAdmin." This step allows tickets to be automatically assigned to the appropriate team, streamlining the resolution process.
</p>
<br />

<p>
<img src="https://i.gyazo.com/61a5575b8b73924312fb231d08ad9404.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Following the creation of departments, I set up a team. Teams are groups of agents who collaborate to handle tickets for specific areas or tasks. I created an “Online Banking” team to ensure specialized support.
</p>
<br />

<p>
<img src="https://i.gyazo.com/a9aa51e77aa02c7cc8aac3fa55d618ad.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/4e5c4d12435e13d9941af3973c1a6ae3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/e30552a1acbc196034c1cc17dd699db6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/0aaf6185d8643de09f1199144052dba5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/48c8b6d6206a68f8243eb9f073418a4c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/c17144b89e6c6853c6271b54505f5e8a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then added two agents to the system and assigned them to specific departments and teams. For example, one agent was assigned to the “SysAdmins” department and the “Online Banking” team, while the other was assigned to the “Support” department and the “Level 1 Support” team. This configuration ensures that each agent focuses on their area of expertise, enhancing efficiency.
</p>
<br />

<p>
<img src="https://i.gyazo.com/dac28647e4ed1e2ce29e7178e77cc57c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I created a user profile. Users represent the customers or end-users who submit tickets.
</p>
<br />

<p>
<img src="https://i.gyazo.com/2b341d957ac3ff24e10ed1208b53c58d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/327ceb626e8ac8a16fb95a39e11c8063.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/0fa438f5f90dc277814ffee351e21e22.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then configured three Service Level Agreements (SLAs). SLAs define the expected response and resolution times for tickets based on their priority.
</p>
<br />

<p>
<img src="https://i.gyazo.com/47e24904b75e9bedaa5935015de055cd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/75c18772e9c35862194ae091c3628683.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/be753f24b31588194fe36c0fc1fe7c96.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/7efb154f56a458ec6028c9c30388fc90.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.gyazo.com/fb79dbb5126172489090074db38b996d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, I created various help topics. Help topics categorize tickets based on common issues, making it easier for users to submit requests and for agents to process them. For instance, I added help topics such as “Business Critical Outage,” “Personal Computer Issues,” “Equipment Request,” “Password Reset,” and “Other.” These topics streamline ticket submission by providing users with predefined categories.
</p>
<br />
