# post-install-config
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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/Tnp8I45.png/>
  <img src=https://i.imgur.com/782zamN.png/>
  <img src=https://i.imgur.com/z6kX83w.png/>
  <img src=https://i.imgur.com/IYapcId.png/>
  <img src=https://i.imgur.com/Tery05U.png/>
  <img src=https://i.imgur.com/fX0Bcdc.png/>
  <img src=https://i.imgur.com/g9qmao8.png/>
  <img src=https://i.imgur.com/G3b9vxX.png/>
  <img src=https://i.imgur.com/Eh6zBGT.png/>
  <img src=https://i.imgur.com/tKuU60D.png/>
  <img src=https://i.imgur.com/Elqw1fg.png/>
  <img src=https://i.imgur.com/hc0p8iY.png/>
  <img src=https://i.imgur.com/Q9AwUHp.png/>
  <img src=https://i.imgur.com/WBuPwed.png/>
  <img src=https://i.imgur.com/L3q8RIS.png/>
  <img src=https://i.imgur.com/fpAFOFC.png/>
  <img src=https://i.imgur.com/t0bIzER.png/>
  <img src=https://i.imgur.com/UZmQSzt.png/>
  <img src=https://i.imgur.com/S6nj1WZ.png/>
  <img src=https://i.imgur.com/Qa91Yl9.png/>
  <img src=https://i.imgur.com/YwCPxeg.png/>
  <img src=https://i.imgur.com/Y5KXWkG.png/>
  <img src=https://i.imgur.com/LnH84Tl.png/>
  <img src=https://i.imgur.com/HjHnIia.png/>
  <img src=https://i.imgur.com/xXlhPVb.png/>
  <img src=https://i.imgur.com/dZWAK9G.png/>
  <img src=https://i.imgur.com/KG4ZV8n.png/>
  <img src=https://i.imgur.com/f4x8JPa.png/>
  <img src=https://i.imgur.com/AutddP6.png/>
  <img src=https://i.imgur.com/a2Ac9h3.png/>
  <img src=https://i.imgur.com/WWWZ6NG.png/>
  <img src=https://i.imgur.com/9rcrEID.png/>
  <img src=https://i.imgur.com/IqB4x5c.png/>
  <img src=https://i.imgur.com/cbvYLPM.png/>
  <img src=https://i.imgur.com/RU5k2Bk.png/>
  <img src=https://i.imgur.com/LQOSwEa.png/>
  <img src=https://i.imgur.com/BgSjtov.png/>
  
</p>
<p>
Now that we've gotten our osTicket setup, let's configure it and get it ready to do some ticketing. To do that, we're going to log in as our adminuser. From here we can see a whole range of tabs. We want to start from the Admin Panel on the top right. 
  
  From there we want to select Agents and then Roles. We can see from the "View only" role, that there are no assigned permissions. In contrast, the "Expanded Access" role has a whole range of permissions selected. You can probably guess what "All Access" permissions look like. We can add our own roles and get specific with them. 
  
  Anyone familiar with having their own Discord server or even Minecraft server should be mildly aware of how this works. Permissions and roles are everywhere! We're going to make our own role "Supreme Admin" that can do everything. This is not unique because we can already do everything, but just in case we wanted a flashy new title. 
  
  Next we'll take a look at Departments and add one of our own. We'll call it SysAdmins, but here we can take a peek at all the settings. Departments can have default SLA's, a Manager, and we can select agents to be a part of this department. We haven't made any Agents yet, but we will and we can add them here. 
  
  We can also create a new Team and get people from different departments to work together. We'll just call them Quality Assurance for the sake of having a name. We can add members from the next tab, but we still need to make some Agents. 
  
  Speaking of Agents, let's make a few! Interjection about allowing end users to make tickets. Anyway, adding an Agent from the Agent tab in the Admin Panel. We're going with John Doe, the classic. We can have this new user set their own password when they first/next log in by ticking this box. We're just going to set one up front. We can set John's Department and Role, any extra permissions and a Team all right here as we're creating him. I'll put him in our new SysAdmins Department and make him a Supreme Admin for the Quality Assurance Team.  I'm going to make a second user named Jane with some different and basic permissions. 
  
  Back over on the Agent's Panel we can get to creating some users. So on the Users tab, we'll add a User and fill out their basic information. This user could be trouble. 
  
  Real quick let's set up SLA's from the Admin Panel on the Manage tab. We'll add a New SLA Plan. Actually we'll make a few of them, in tiers. This all depends on what we're trying to accomplish in each tier, but this will help us sort out our tickets down the line. Grace Periods indicate how long we have before the ticket is marked Overdue. Schedule check which hours will contribute to a ticket being overdue. 24/7 or business hours and such. We'll make a few example SLA's in varying tiers of urgency. 

  All we really need from here is a way for the end users (or us) to give a heads up with their problems when they generate a ticket. We'll configure the Help Topics. We can add a new Help Topic here. We just name our topic(s) and set what kind of parent topic it belongs to, like Reporting a Problem or Feedback.

  With our topics set up, we have everything we need to get things started on a ground level!
</p>
<br />

<p>
text
</p>
<p>
image
</p>
<br />


