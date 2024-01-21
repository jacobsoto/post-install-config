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

- Microsoft Azure (Virtual Machines/Compute)

- Remote Desktop Connection

- OsTicket
 


<h2>Configuration Steps</h2>

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/7f3adce9-2edc-49c4-b6f4-44d27d2b568c)


![image](https://github.com/jacobsoto/post-install-config/assets/156248197/bfc3740c-4501-4e99-a48e-c9bb6d05ff21)

 After installing osTicket, it is now time to make configurations to use it as a ticketing system. One thing to note is that I switch between Admin and Agent panels as each panel has different configurations. To tell which panel is used, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

The first step to take is to make a new role called Supreme Admin. For the purposes of this lab, I am intentionally creating a role that has every permission that can be granted. To create a new role, open the Admin panel enter the Agents Menu. Click on Roles and create the new role from there.

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/786c6dc1-9a2b-4bcc-ab88-364088f96d0b)

 Next, a new Department will be created for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/11e9cf52-0803-4d13-af91-cd95dd1641ea)


A new Level II Support Team will have to be created to supplement the Level I Support Team already made within osTicket. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created.

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/aaf5cace-f5ac-44dd-b974-e1b0a5a59433)


![image](https://github.com/jacobsoto/post-install-config/assets/156248197/f62c9cc5-f7da-4a6a-9b73-8b9105cee857)


 New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Jane and John Doe are created.

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/0b1f209f-8f0b-4bcf-b875-36fc89b5ca8a)


 New users will be created so they can create tickets so that the agents can receive and triage them. To create new users, enter the Agents panel and open the Users menu. Click on Add User and create the account credentials necessary for each new user. In this case, Karen and Ken have been created.

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/eb650964-24cb-497f-8fc2-9cc914b9761b

Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively. 

![image](https://github.com/jacobsoto/post-install-config/assets/156248197/dad63ceb-a5ed-49fb-a8fa-ae24e98c8e54)

 Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.




Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
















 




