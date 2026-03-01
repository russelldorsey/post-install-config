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

- Admin Panel vs Agent Panel
- Configure Roles
- Configure Departments
- Configure Teams
- Configure User Settings
- Configure Agents
- Configure Users
- Configure SLA

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

After reviewing the settings to ensure the correct access levels are selected, click Add Role or Save Changes to create the role. Once the role is created, you can assign it to a staff member from the Agents section so they receive the designated permissions.
</p>
<br />

<p>
<img width="954" height="1030" alt="Screenshot 2026-03-01 104103" src="https://github.com/user-attachments/assets/4e1d5efb-f94d-4e47-8323-8f0b31916771" />
</p>
<p>
To add a new Department in osTicket, log in to the Admin Panel, click the Agents tab, then select Departments. Click Add New Department to begin. Enter a name for the department (such as SysAdmins, Support, or IT Help Desk) and, if needed, assign a Department Manager. You can also configure settings such as the department’s email address, ticket assignment options, and visibility. Departments help organize tickets by category or function, ensuring they are routed to the appropriate team. After reviewing the settings, click Create Department or Save Changes to finish.
</p>
<br />

<p>
<img width="957" height="1036" alt="Screenshot 2026-03-01 105644" src="https://github.com/user-attachments/assets/af0d0fef-ada0-4e31-9caa-32a7f0e124ee" />
</p>
<p>
To add a new Team in osTicket, log in to the Admin Panel and click on the Agents tab, then select Teams. Click Add New Team to begin. Enter a clear team name (such as Online Banking, Level II Support, or Network Team) and select a Team Lead if desired. You can then add team members by selecting agents who may be part of the team. Teams allow you to group agents from different departments so tickets can be assigned based on expertise rather than department alone. After reviewing the settings, click Create Team or Save Changes to complete the setup.
</p>
<br />

<p>
<img width="956" height="1039" alt="Screenshot 2026-03-01 112037" src="https://github.com/user-attachments/assets/f5f47c37-5395-4efa-ac45-5461a5f70d48" />
</p>
<p>To set up User Settings in osTicket, log in to the Admin Panel and click on the Settings tab, then select Users. In this section, you can configure how user accounts function within the help desk system. Choose whether users are required to register before submitting tickets (check or uncheck Registration Required: Require registration and login to create tickets), enable or disable email verification, and decide if users can create accounts automatically when they submit a ticket. You can also adjust authentication options and account management preferences. These settings control how customers interact with the system and help balance security with ease of access. After making your selections, click Save Changes to apply the updates. 
</p>
<br />

<p>
<img width="958" height="1033" alt="Screenshot 2026-03-01 114403" src="https://github.com/user-attachments/assets/780ab971-4e9a-494b-848f-5b526a293f06" />
</p>
<p>
To add an Agent in osTicket, log in to the Admin Panel and select the Agents tab. Click Add New Agent (or Add New Staff Member, depending on your version). Enter the agent’s name, email address, and username, then create a password for their account. Next, open the Access tab to assign the agent to a Department, then choose the appropriate Role, which determines the permissions they will have in the system. While on the Access tab, carefully review the settings to ensure the agent has the correct permissions to handle tickets and tasks. If necessary, go to the Teams tab to add the agent to a specific team. Once everything is set up correctly, click Create or Save Changes to complete the process.
</p>
<br />

<p>
<img width="957" height="1036" alt="Screenshot 2026-03-01 121153" src="https://github.com/user-attachments/assets/3c53dcd9-4e3a-48c3-b2b4-bbd5fdbc051e" />
</p>
<p>
To add a User in osTicket, log in to the Agent Panel, as users (also called end users) are managed there rather than in the Admin Panel. Click on the Users tab, then select Add User. Enter the user’s name and email address, which will be used for ticket communication and notifications. You can also add additional contact information if needed. Users are the people who submit support requests, so adding them allows agents to create and manage tickets on their behalf. After entering the required information, click Add User or Create to save the new user account.
</p>
<br />

<p>
<img width="956" height="1037" alt="Screenshot 2026-03-01 122427" src="https://github.com/user-attachments/assets/b5a6cb99-38da-467a-b76a-a1ca8bad135b" />
</p>
<p>
To add an SLA (Service Level Agreement) in osTicket, log in to the Admin Panel and click on the Manage tab, then select SLA. Click Add New SLA Plan to create a new SLA. Enter a name for the SLA (such as Sev-A, 24-Hour Response, or 48-Hour Resolution) and set the Grace Period, which defines how long agents have to respond to or resolve a ticket. You can also choose a Schedule, such as business hours or 24/7 coverage, to control when the SLA timer runs. SLA plans help ensure tickets are handled within specific time limits and allow the system to track overdue requests. After configuring the settings, click Add Plan or Save Changes to finish creating the SLA.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
