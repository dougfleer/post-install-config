<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- **Microsoft Azure**: Demonstrating cloud platform proficiency with Virtual Machines and resource management.
- **Remote Desktop**: Leveraging remote tools for efficient system access and management.
- **Internet Information Services (IIS)**: Configuring and optimizing web servers for application hosting.

<h2>Operating Systems Used</h2>

- **Windows 10 (21H2)**

<h2>Post-Install Configuration Objectives</h2>

1. Configure Roles and Permissions for users.
2. Create and manage Departments for ticket visibility.
3. Configure Teams to pull agents from different departments.
4. Enable and assign SLAs (Service Level Agreements) for ticket resolution timelines.
5. Set up Help Topics for ticket categorization.

<h2>Configuration Steps</h2>

### Step 1: Configure User Roles
1. Navigate to **Admin Panel > Agents > Roles**.
2. Create and assign a new role "Supreme Admin" with full permissions.

### Step 2: Set Up Departments
1. Go to **Admin Panel > Agents > Departments**.
2. Create departments such as "SysAdmins" and "Networking".

### Step 3: Configure Teams
1. Navigate to **Admin Panel > Agents > Teams**.
2. Assign agents from multiple departments to teams like "Online Banking".

### Step 4: Configure SLAs
1. Access **Admin Panel > Manage > SLA**.
2. Create SLA plans:
   - Sev-A: 1 hour (24/7 schedule)
   - Sev-B: 4 hours (24/7 schedule)
   - Sev-C: 8 hours (Business Hours schedule)

### Step 5: Create Help Topics
1. Go to **Admin Panel > Manage > Help Topics**.
2. Add topics like "Business Critical Outage," "Password Reset," and "Personal Computer Issues".
