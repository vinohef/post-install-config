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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (For grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (for when users create a ticket)

<h2>Configuration Steps</h2>

Log into your Admin/analyst page 
<p>
<img src="https://i.imgur.com/8jrm4DH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Configure roles</h2>

Go to the Admin Panel

<p>
<img src="https://i.imgur.com/l5lTAK6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>

Go to the Agents tab

<p>
<img src="https://i.imgur.com/l3jJAWg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>
Select Roles

<p>
<img src="https://i.imgur.com/zXKeVUs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>
Click Add New Role

<p>
<img src="https://i.imgur.com/KEgjcJm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>

Name the Role "Supreme Admin"
<p>
<img src="https://i.imgur.com/KkZLQIk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>

Give this Role permission to do everything (check every box under Tickets, Tasks, and Knowledgebase)
<p>
<img src="https://i.imgur.com/XFU0ZKq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2>Configure Departments</h2>

Inside the same Agents tab select departments
<p>
<img src="https://i.imgur.com/2Op9euN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>

Name the department "SysAdmins"
<p>
<img src="https://i.imgur.com/YjxBuNY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />



<p>
<img src="https://i.imgur.com/qPCTjK7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Configure Teams</h2>

Next go to the Teams tab
<p>
<img src="https://i.imgur.com/haZzCUf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />


Select "Add New Team"
<p>
<img src="https://i.imgur.com/H4YsTYe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />


Name the Team "Online Banking"
<p>
<img src="https://i.imgur.com/HTH4LQi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Allow anyone to create tickets</h2>

Go to the settings tab
<p>
<img src="https://i.imgur.com/dBS4M7D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Under the User settings make sure "Require registration and login to create tickets" is unchecked

<p>
<img src="https://i.imgur.com/XhjLhjF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Configure Agents (workers)</h2>

Go back to the Agents tab
<p>
<img src="https://i.imgur.com/OdcWeYq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Select "Add New Agent"

<p>
<img src="https://i.imgur.com/qt9hr0R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Fill out the Name, email, and Username (email has to be a valid one). Remember the Usernames you use.

<p>
<img src="https://i.imgur.com/xNNwIbQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Now go the Access tab and put this agent in the SysAdmins group and give him the Supreme Admin role.
<p>
<img src="https://i.imgur.com/x7HQZyM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Create another agent BUT put it in the Support department (DONT give it the Supreme Admin Role)

<h2>Configure users</h2>

Go to the Agent Panel at the top

<p>
<img src="https://i.imgur.com/EghUism.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Go to the Users tab

<p>
<img src="https://i.imgur.com/FKbHrya.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Select Add User

<p>
<img src="https://i.imgur.com/zZr37Ec.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Fill out the Email and Full name parts

<p>
<img src="https://i.imgur.com/KmBikbP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2>Configure SLA</h2>

Go to the Admin Panel

<p>
<img src="https://i.imgur.com/BwtMO9k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Find the Manage tab

<p>
<img src="https://i.imgur.com/k6nByxr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Click SLA

<p>
<img src="https://i.imgur.com/dAj1uK4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Click Add New SLA Plan

<p>
<img src="https://i.imgur.com/pCMCHjK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<h2></h2>

<p>
<img src="https://i.imgur.com/GINvV9O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create 3 SLA Plans (Name them Sev-A, Sev-B, and Sev-C)
|Sev-A (Grace Period: 1 hour, Schedule: 24/7)|   
|Sev-B (Grace Period: 4 hours, Schedule: 24/7)|
|Sev-C (Grace Period: 8 hours, Schedule : Buisness hours)|  
</p>
<br />


<h2></h2>

<h2>Configure Help Topics</h2>

Go to Help Topics

<p>
<img src="https://i.imgur.com/To6xXkY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<h2></h2>



<p>
<img src="https://i.imgur.com/T7HVRzw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Create these help topics and name them as follows:
  |Buisness Critical Outage|
  |Personal Computer Issues|
  |Equipment Request|
  |Password Reset|
  |Other|
</p>
<br />
<h2></h2>

