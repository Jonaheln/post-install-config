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

- Item 1 Create Users
- Item 2 Create Departments
- Item 3 Agent Roles and Permissions
- Item 4 Ticket Forms and Custom Fields
- Item 5 Role-based Access Control (RBAC)

<h2>Configuration Steps</h2>

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

![image](https://github.com/user-attachments/assets/38a60eee-2296-40ea-977d-7b8dad03a974)

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

![image](https://github.com/user-attachments/assets/32e92fa3-45e0-453c-897f-a5d373ff194b)

- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

![image](https://github.com/user-attachments/assets/67d40bb3-e02d-4603-a1dd-cde9eda3ab28)

- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)


![image](https://github.com/user-attachments/assets/d87aefd7-2fe1-4f37-984a-8190972d3449)

- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


![image](https://github.com/user-attachments/assets/d2af7b9e-2676-467b-baac-e1104483d520)




