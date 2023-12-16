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
Next we will create a new Level II Support Team to supplement the Level I Support Team that already exists within osTicket. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created. 
</p>

![setting up iis -69](https://github.com/Jacob-Oq/post-install-config/assets/150084528/b4720acc-f5e5-4727-adc8-32865921c9ed)


<br />
