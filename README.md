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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Create new admin role
- Configure Worker team
- Configure Customer team 
- Develop ticketing system

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/GHZm6VF.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 1: Go to Admin Panel, Agents (Under Dashboard), then Roles. Create a new role called "Supreme Admin" with every permission. 
</p>
<br />

<p>
<img src="https://imgur.com/H1hUDg5.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 2: Then navigate to the departments tab. Create a new department named "System Administrators".
</p>
<br />

<p>
<img src="https://imgur.com/UXUriRA.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 3: Go to the teams tab next and create two new teams named "Level I Support" and "Level II Support"
</p>
<br />

<p>
<img src="https://imgur.com/XDrsHED.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 4: Access settings in the Admin panel, go to user settings, and apply "Require Registration and login to create tickets"
</p>
<br />

<p>
<img src="https://imgur.com/sNWlHQD.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 5: In Admin panel, create two new agents: Jane and John. Apply all permissions and make sure to add them to a team. (Support and above)
</p>
<br />

<p>
<img src="https://imgur.com/ucw6piD.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 6: In Agent panel, create two new users: Karen and Ken.
</p>
<br />

<p>
<img src="https://imgur.com/GcQ7dBa.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 7: Under Admin panel, go to Manage and create three new SLAs (Service Level Agreement), each named Sev A, Sev B, and Sev C. For Sev A, set it for 1 hour GP and a 24/7 schedule. For Sev B, set it for 4 hours GP and 24/7 schedule. For Sev C, set it for 8 hours GP and Business hours schedule. 
</p>
<br />

<p>
<img src="https://imgur.com/GKb0aeU.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 8: In Manage, create four Help Topics. Business Critical Outage (Priority Emergency, Sev A, System Administrators), Personal Computer Issues (Priority High, Sev B, Support), Equipment Request (Priority Low, Sev C, Maintenance), Password Reset (Priority Normal, Sev B, Support). This is the final step, you can now create and solve tickets in mock situations! 
</p>
<br />
