<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable and install IIS (Internet Information Services)
- Installing PHP Manager for IIS
- Creating a directory for PHP 
- Installing VC_redist.86.exe
- Installing MySQL 5.5.62
- Install osTicket v1.15.8
- Install HeidiSQL

<h2>Installation Steps</h2>

<p>



<img src="https://i.imgur.com/NYIKImI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Download and unzip os-Ticket installation files



<img src="https://i.imgur.com/Zk0SPiY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Before proceeding with any downloads, enable CGI in IIS. 

<img src="https://i.imgur.com/Kxg1xX4.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/YjEUrye.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Go back to the os-Ticket installation files folder and install PHP Manager and the rewrite module.

<img src="https://i.imgur.com/jnLjArY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Create a directory for PHP

<img src="https://i.imgur.com/PsUpivl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Extract the PHP folder into the created PHP directory

<img src="https://i.imgur.com/KJ3E86D.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/7NmsrYb.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> 

Install VC_redist.86.exe and MySQL

<img src="https://i.imgur.com//rDWcjZm.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/v40USMN.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Configure MySQL

<img src="https://i.imgur.com/H2PMSga.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/04NvY46.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Register a new PHP version and choose the php-cgi.exe file that can be found in the PHP directory created previously.

<img src="https://i.imgur.com/v1vg2WK.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/iO6VfUU.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Extract the os-Ticket-v1.15.8 into


