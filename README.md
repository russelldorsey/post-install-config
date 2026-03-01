<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- osTicket Admin Panel vs Agent Panel
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="1914" height="1035" alt="Screenshot 2026-03-01 095145" src="https://github.com/user-attachments/assets/688053eb-24cb-468c-807f-a1eb9b351a3b" />
</p>
<p>
In osTicket, the Admin Panel and the Agent Panel serve different roles within the help desk system.

The Admin Panel is used to manage and configure the entire system. Administrators set up departments, roles, teams, email settings, ticket rules, and system preferences. They control user permissions, manage staff accounts, and customize how osTicket functions overall. In short, the Admin Panel focuses on system setup and oversight.

The Agent Panel, on the other hand, is where support staff handle daily ticket operations. Agents view, respond to, assign, and close tickets submitted by users. They communicate with customers, add internal notes, and update ticket statuses. The Agent Panel is centered on resolving support requests rather than configuring the system.
</p>
<br />

<p>
<img width="954" height="1030" alt="Screenshot 2026-03-01 103556" src="https://github.com/user-attachments/assets/b773a1cc-bba7-4cfa-bf7f-b77a8a977121" />
</p>
<p>
To add a Supreme Admin role—or create any new role—in osTicket, begin by logging in to the Admin Panel, which is where all system configuration and staff permissions are managed. Once logged in, click on the Agents tab and select Add New Role. On the Definition tab, enter a clear and descriptive name for the role, such as Supreme Admin, so it is easy to identify later.

Next, navigate to the Permissions tab. Here, you can control what users assigned to this role are allowed to do within the system. Under the Tickets and Tasks sections, check all permissions you want the role to have, such as viewing, creating, editing, assigning, closing, and deleting. Granting full permissions will allow the user to manage tickets and tasks without restrictions.

After reviewing the settings to ensure the correct access levels are selected, click Add Role to create the role. Once the role is created, you can assign it to a staff member from the Agents section so they receive the designated permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
