<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial walks you through setting up osTicket, the open-source help desk ticketing system, after installation.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Logging in
- Configuring Roles
- How to configure Departments
- How to configure Teams
- How to configure Agents
- How to configure Users (Customer)
- Configure SLA's and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/enyNIgM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Step 1: Logging In

Admin/Analyst (Staff) Login
 
 -Go to: http://localhost/osTicket/scp/login.php
 
 Enter your administrator or staff credentials to access the Staff/Agent Panel and Admin Panel.


End User Portal
 
 -Your customers can access the end user portal at: http://localhost/osTicket

Here, they can create new tickets (if allowed) and check ticket statuses


</p>
<br />



<p>
<img src="https://i.imgur.com/LwZcZdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Configuring Roles
  
  Accessing Roles
 
   -Navigate to Admin Panel → Agents → Roles.

 Roles dictate what agents can see and do (e.g., delete tickets, transfer tickets, manage users).


  Create a New Role
 
   -Click Add New Role to define a name and permissions.

Example: Supreme Admin (a role with full access to all settings).

   Assign Roles to Agents
 
   -When creating or editing an agent, select the desired role to match their responsibilities.



</p>
<br />



<p>
<img src="https://i.imgur.com/W8L1ekA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: How to Configure Departments

  
  Departments Overview

   -Departments organize ticket visibility and workflows. Common departments include Support, SysAdmins, Networking, etc.
 
  Creating or Editing Departments

   -Go to Admin Panel → Agents → Departments.

   -Click Add New Department or edit an existing department.

   -Set a department name, email address (if desired), and department manager.

   -Assign Agents to Departments

  Each agent can be part of one or multiple departments based on their role in the organization.
</p>
<br />



<p>
<img src="https://i.imgur.com/XM3TJ1G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: How to Configure Teams
  Teams vs Departments

  Teams are cross-functional groups of agents who may belong to different departments but work together on specific projects or ticket types.
  
Creating a Team

 -Access Admin Panel → Agents → Teams.
 
 -Click Add New Team and give it a descriptive name, (ex. Online Banking)
 
Assign Agents to Teams

  -Select agents from various departments to collaborate on specialized tickets or high-priority issues.
</p>
<br />



<p>
<img src="https://i.imgur.com/6yFBjx6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: How to Configure Agents
  
  Adding Agents (Staff)

  -Go to Admin Panel → Agents → Add New.

  -Input the agent’s name, email, username, and password.

  Assign Departments & Roles

  -Select the department(s) an agent belongs to.

  -Assign the appropriate role (e.g., Support, SysAdmins, Supreme Admin).
  
  Agent Permissions

  -Decide which agent actions are allowed, such as creating tickets, editing tickets, or managing users.
</p>
<br />



<p>
<img src="https://i.imgur.com/Ks061ix.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: How to Configure Users (Customers)
  
  Adding New Users

  -In the Agent Panel, go to Users → Add New.
  
  -Fill in the user’s name, email, and other relevant details (phone number, organization, etc.).


  Registration & Ticket Creation Settings

  -Admin Panel → Settings → User Settings
  
  -Decide if unregistered users can create tickets or if registration is required.
  
Managing Users

  -Users can be manually added by staff or self-register (depending on your settings).

  -Group users under “Organizations” if needed (helpful for corporate clients or schools).
</p>
<br />



<p>
<img src="https://i.imgur.com/5sUbj1j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7.1: SLAs (Service Level Agreements)
  Accessing SLAs

  -Go to Admin Panel → Manage → SLA.

  -SLAs define response and resolution time frames.

  Common SLA Examples:

  -Sev-A: 1-hour grace period, 24/7 schedule (critical).

  -Sev-B: 4-hour grace period, 24/7 schedule (urgent but less critical).

  -Sev-C: 8-hour grace period, business hours (normal priority).


  Assign SLA Plans

  -You can assign different SLAs to help topics, departments, or ticket filters so they automatically apply based on ticket classification.

  <img src="https://i.imgur.com/75sda2O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Step 7.2: Help Topics

  Help Topics Overview

  Help Topics guide end users in categorizing their support requests (e.g., Password Reset, Equipment Request, Business Critical Outage).

  Creating Help Topics

  -Admin Panel → Manage → Help Topics.

  -Click Add New Help Topic and name it (e.g., “Personal Computer Issues”).

  Organizing Help Topics

  -Maintain a clear list so end users can quickly find the correct category, ensuring tickets route efficiently.
</p>
<br />
