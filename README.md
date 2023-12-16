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

<h2>Configuration Steps</h2>

<p>
Now that we have succesfully installed osTicket, it's time to make configurations to use it as a ticketing system. Each panel that is used has different configurations. To know which panel is active, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

Let's make a new role called Supreme Admin. We will intentionally create a role that has every permission that can be granted. Open the Admin panel and enter the Agents Menu. Click on Roles and create the new role from there.
</p>

![setting up iis -62](https://github.com/Jacob-Oq/post-install-config/assets/150084528/166abd70-d2dc-4855-92cf-81fd5668b9e0)

<br />

<p>
Next, let's create a new "Department" for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.
</p>

![setting up iis -63](https://github.com/Jacob-Oq/post-install-config/assets/150084528/dfb7f11e-2b06-4129-9621-4b8b55875dd7)

<p>Be sure to name the department for it's use. In this case it will be "System Adminstrators"</p>

![setting up iis -64](https://github.com/Jacob-Oq/post-install-config/assets/150084528/4b24f595-b258-4f50-9ed6-b1685834ab81)


<br />
<p>
Next we will create a new Level II Support Team to supplement the Level I Support Team that already exists within osTicket. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add the new team to be created. You can add more if needed.
</p>

![setting up iis -69](https://github.com/Jacob-Oq/post-install-config/assets/150084528/b4720acc-f5e5-4727-adc8-32865921c9ed)


<br />

<p>Now we can create new agents so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent.</p>

![setting up iis -67](https://github.com/Jacob-Oq/post-install-config/assets/150084528/c8cdd122-a57b-4bd3-8520-b0a4ac297bbc)

![setting up iis -74](https://github.com/Jacob-Oq/post-install-config/assets/150084528/6671ff81-00b9-428e-b8ab-29ec04897003)


<br />
<p>New users will be created so they can create tickets so that the agents can receive and triage them. To create new users, enter the Agents panel and open the Users menu. Click on Add User and create the account credentials necessary for each new user. In this case, Karen and Ken have been created. </p>

![setting up iis -76](https://github.com/Jacob-Oq/post-install-config/assets/150084528/8a040f7b-2f03-495e-88b5-e0857efc9ca3)

![setting up iis -77](https://github.com/Jacob-Oq/post-install-config/assets/150084528/7b3ffaf0-1b34-47b4-843a-412612d72702)

![setting up iis -78](https://github.com/Jacob-Oq/post-install-config/assets/150084528/2e791a76-3246-4376-9757-86f70430e6bf)


<br />

<p>Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact.</p>

![setting up iis -79](https://github.com/Jacob-Oq/post-install-config/assets/150084528/277da10d-a03d-4866-a450-24ed8b340a6c)

  
<p>To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C will be created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively. </p>

![setting up iis -80](https://github.com/Jacob-Oq/post-install-config/assets/150084528/083bf983-ba26-46e8-b9eb-53c185b88a96)

![setting up iis -81](https://github.com/Jacob-Oq/post-install-config/assets/150084528/16e13990-641a-4e31-89f4-8b418941ec7d)

![setting up iis -82](https://github.com/Jacob-Oq/post-install-config/assets/150084528/840c1529-6b1b-4637-809e-5f20ac986e56)


![setting up iis -83](https://github.com/Jacob-Oq/post-install-config/assets/150084528/2d844a10-88a4-466a-9dee-2fd3fef61e27)






