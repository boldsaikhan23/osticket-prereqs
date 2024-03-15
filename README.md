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

- Enable IIS in Windows with CGI
- Install PHP Manager for IIS 
- Install Rewrite Module 
- Install PHP
- Visual C++
- MySQL

<h2>Installation Steps</h2>


<p>
<img src="https://i.imgur.com/1A4pu7L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h4>

-Download osTicket 

-Extract and copy “upload” folder to c:\inetpub\wwwroot

-Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

-Open IIS, click on sites -> Default -> osTicket

-On the right, click “Browse *:80”


</h4>
<br />

<p>
<img src="https://i.imgur.com/8AUmeCD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue setting up osTicket in the browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/KzQQ29Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h5>
-Download HeidiSQ
-Create a new session, root/Password1
-Connect to the session
-Create a database called “osTicket"

</h5>
<br />
