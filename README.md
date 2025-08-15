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

- Windows 11 Pro</b> (24H2)

<h2>Post-Install Configuration Objectives</h2>

- Secure and Customize Agent & User Access
- Define Ticket Visibility and Permissions
- Configure SLAs (Service Level Agreements)
- Set Up Help Topics
- Finalize System Behavior

<h2>Configuration Steps</h2>

<p> 
Step 1: Log in to osTicket
</p>

<p> + Browse to the osTicket Admin/Analyst login page (http://localhost/osTicket/scp/login.php) and enter your credentials</p>
<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%201.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <br />

<p>
Step 2: Configure Roles
</p>
<p> + Go to Admin Panel -> Agents -> Roles</p>
<p> + Click "Add New Role"</p>
<p> + Name it "Supreme Admin"</p>
<p> + Click "Permissions", under "Tickets" select every option</p>
<p> + Under "Tasks" select every option</p>
<p> + Under "Knowledgebase" select every option and then click "Add Role"</p>
<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%202.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%202b.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%202c.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%202dd.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%202%20permissions,%20tasks.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%202g.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Step 3: Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
<p>

<p> + In the Admin Panel, Agents -> Departments -> "Add New Department"</p>
<p> + Name it "SysAdmins" and click "Create Dept"</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%203.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://github.com/bigbearbunkie/osTicket-Post-Installation-Configuration/blob/main/Post%20install%20step%203b.PNG?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Step 4: Configure Teams
</p>

<p> + In the Admin Panel, Agents -> Teams -> "Add New Team"</p>
<p> + Name it "Online Banking" and click "Create Team"</p>

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
