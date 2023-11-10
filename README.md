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

- Configure Departments
- Configure Agent (Employee)
- Configure Roles
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/m9l3cPS.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The configuration of departments was performed within the Admin Panel, specifically in the Agents tab. Departments play a pivotal role in routing tickets within the help desk system. These departments can be categorized as either private or public, and they offer the flexibility to be assigned to one or more agents and managers.
</p>
<br />

<p>
<img src="https://i.imgur.com/AQuoylX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents were set up and granted access to the help desk with the purpose of handling and resolving tickets. During the agent addition process, they can be linked to a primary department and provided with a primary role specifically for handling tickets and tasks routed to that particular department. Agents may also receive extended access to other departments within the help desk and can be assigned distinct roles for those particular departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/8Dv6JBq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles represent the permissions allocated to agents on a department-specific basis. Each role is equipped with a defined set of permissions that can be customized by checking or unchecking specific options for agents holding that role within their associated department. An unlimited number of roles can be established and assigned to agents who have access to different departments. Configuration of these roles is accomplished within the Admin Panel, specifically in the Agents tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/wTNz3GI.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans, or Service Level Agreements, are designed to stipulate the expected timeframe within which the help desk administrator anticipates tickets to be resolved. To create SLA Plans, navigate to the Manage tab within the Admin Panel and select "Add New SLA Plans." This allows for the establishment of specific service level agreements.
</p>
<br />
