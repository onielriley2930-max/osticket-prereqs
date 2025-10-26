<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install a Web Server (Internet Information Service IIS)
- PHP
- Install IIS URL Rewrite Module
- Ceate the directory C/PHP
- Install VC redist
- Install MySQL
- install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/yvRJsIf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- First,we install a Internet Information Service (IIS) in our virture machice to run osticket on. In our virture machine we hit the window command start button and select control panel option, double click to open its windowns on/off features. At this point, we activated our IIS and CGI features. Then we use the loop function 127.0.0.1 to default web page, to verify we have a working web server and it should look like the photo above. From here on it is our web browser and user have access to helpdesk system.
</p>
<br />

<p>
<img src="https://imgur.com/6kG7rsD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next is our PHP from our osticket file folder, we would install PHP manager. This is the language osticket understands and run well in.
</p>
<br />

<p>
<img src="https://imgur.com/qeVQvMC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we would install IIS URL Rewrite Module.This mod_rewrite is an Apache web server module used to rewrite URLs. It allows web applications like osTicket to have clean, user-friendly URLs (
</p>
<br />    
<p>
<img src="https://imgur.com/KJ68bjd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/KfKwLFq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next we create a Directory in our Windows C Drive. To do that, we create a new folder and named it C/PHP, and then unzip osticket installation zip files into folder created.
</p>
<br />
<img src="https://imgur.com/jpLENsk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next we install VC Redist. THis is just another extention osticket required in order to use.
</p>
<br />
<img src="https://imgur.com/w2MAhAU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/os80hY8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/Vihrn7Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/lFXUJNG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next we install MYSQL.This is our database that osticket use to store all of our data in. From all the users account, ticketing informations, in the backend. After installing, we launch MYSQL configuration wizards and choose standard configurations. After that, we registered PHP manager within IIS, think of it as making IIS aware of the existing file on the computer. Then we stop and restart the web server. From this point we open the osticket zip file and install osticket
</p>
<br />
<img src="https://.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next we install MYSQL.This is our database that osticket use to store all of our data in. All the users account, ticketing information, in the backend. After installing, we launch MYSQL configuration wizards and choose standard configurations.
</p>
<br />
