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

- Create Role
- Create Department
- Create Team
- Create Agent
- Create User
- Create SLA

<h2>Configuration Steps</h2>

<p>
1) With osTicket setup and installed we need to configure it and get it ready to do some ticketing. I'm going to log in as the adminuser I created upon install. It opened to the Agent Panel, but I want to navigate to the Admin panel from the top right.
</p>
<p>
<img src=https://i.imgur.com/Tnp8I45.png/>
  <img src=https://i.imgur.com/782zamN.png/>
  <img src=https://i.imgur.com/z6kX83w.png/>
</p>
<br />

<p>
2) From there I want to select Agents and then Roles. When I check the roles, I can see from the "View only" role that there are no assigned permissions. In contrast, the "Expanded Access" role has a whole range of permissions selected. You can probably guess what "All Access" permissions look like. I'm going to add my own role and give it some permissions. 
</p>
<p>
<img src=https://i.imgur.com/IYapcId.png/>
  <img src=https://i.imgur.com/Tery05U.png/>
  <img src=https://i.imgur.com/fX0Bcdc.png/>
  <img src=https://i.imgur.com/g9qmao8.png/>
  <img src=https://i.imgur.com/G3b9vxX.png/>
</p>
<br />

<p>
Anyone familiar with Discord servers or even Minecraft servers should be aware of roles and permissions, they're everywhere. I'm going to make a new "Supreme Admin" role that can do everything. This is not unique because I can already do everything, but it's flashy. 
</p>
<p>
<img src=https://i.imgur.com/Eh6zBGT.png/>
  <img src=https://i.imgur.com/tKuU60D.png/>
</p>
<br />

<p>
3) Next to add a Department of our own. I'll call it SysAdmins. You can see that Departments can have default SLA's, a Manager, and we can select agents to be a part of this department. I haven't made any Agents yet, but they can be added here.
</p>
<p>
<img src=https://i.imgur.com/Elqw1fg.png/>
  <img src=https://i.imgur.com/hc0p8iY.png/>
  <img src=https://i.imgur.com/Q9AwUHp.png/>
  <img src=https://i.imgur.com/WBuPwed.png/>
</p>
<br />

<p>
4) Then I'll create a new Team so people from different Departments to work together. I'll just call it Quality Assurance, but it could be named anything. Just as before, Agents can be added here as members.
</p>
<p>
 <img src=https://i.imgur.com/L3q8RIS.png/>
  <img src=https://i.imgur.com/fpAFOFC.png/>
  <img src=https://i.imgur.com/t0bIzER.png/>
</p>
<br />

<p>
  5) As a sidenote, we need to allow end users to make their own tickets. I'm turning off the requirement to register before making tickets, but I'm still going to make a user for demonstrating the ticket process later.
</p>
<p>
<img src=https://i.imgur.com/UZmQSzt.png/>
  <img src=https://i.imgur.com/S6nj1WZ.png/>
</p>
<br />

<p>
6) Now, I'll create an Agent from the Agent tab in the Admin Panel. Just going with John Doe for simplicity. We can have this new user set their own password when they first/next log in by ticking this box. I'm going to set one up front to avoid that. You can set an Agent's Department and Role, any extra permissions and a Team right as they are created. I'll put him in our new SysAdmins Department and make him a Supreme Admin for the Quality Assurance Team. I'm going to make a second user named Jane with some different and basic permissions.
</p>
<p>
 <img src=https://i.imgur.com/Qa91Yl9.png/>
  <img src=https://i.imgur.com/YwCPxeg.png/>
  <img src=https://i.imgur.com/Y5KXWkG.png/>
  <img src=https://i.imgur.com/LnH84Tl.png/>
  <img src=https://i.imgur.com/HjHnIia.png/>
  <img src=https://i.imgur.com/xXlhPVb.png/>
  <img src=https://i.imgur.com/dZWAK9G.png/>
</p>
<br />

<p>
7) Returning to the Agent's Panel I'll create a user to work with. On the Users tab, I'll add a User and fill out their basic information. When learning, it's always best to have some fun, so this user is admittedly fun.
</p>
<p>
<img src=https://i.imgur.com/KG4ZV8n.png/>
  <img src=https://i.imgur.com/f4x8JPa.png/>
  <img src=https://i.imgur.com/AutddP6.png/>
  <img src=https://i.imgur.com/a2Ac9h3.png/>
</p>
<br />

<p>
8) I'm going back to the Admin panel to set up SLA's from the Manage tab. I'll add a few New SLA Plans, in tiers. Depending on what we're trying to accomplish in each tier, these settings will help us sort out our tickets down the line. Grace Periods indicate how long we have before the ticket is marked Overdue. Schedule checks which hours will contribute to a ticket being overdue, like 24/7 or business hours only. We'll make a few example SLA's in varying tiers of urgency. Forgive me, I only screenshot one of the SLA's, but I made three. 
</p>
<p>
 <img src=https://i.imgur.com/WWWZ6NG.png/>
  <img src=https://i.imgur.com/9rcrEID.png/>
  <img src=https://i.imgur.com/IqB4x5c.png/>
</p>
<br />

<p>
 9) All that's really needed from here is a way for the end users (or us) to give a heads up with their problems when they generate a ticket. I'll configure the Help Topics for this, so we'll just add a new one. Just name the topic(s) and set what kind of parent topic it belongs to, like Reporting a Problem or Feedback.
</p>
<p>
  <img src=https://i.imgur.com/cbvYLPM.png/>
  <img src=https://i.imgur.com/RU5k2Bk.png/>
  <img src=https://i.imgur.com/LQOSwEa.png/>
  <img src=https://i.imgur.com/BgSjtov.png/>
</p>
<br />

<p>
With our topics set up, we have everything we need to get things started on a ground level!
</p>
<br />
