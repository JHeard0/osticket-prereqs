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

<h2>Download and unzip os-Ticket installation files<h2>

![Download and Unzip osTicket](https://raw.githubusercontent.com/JHeard0/osticket-prereqs/refs/heads/main/Download%20and%20Unzip%20os-Ticket.png)




<h2>Before proceeding with any downloads, enable CGI in IIS <h2> 

![Enable CGI in IIS](https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Enable%20CGI%20in%20IIS.png)


<h2>Install PHP Manager and the rewrite module<h2>
  
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/PHP%20Manager%20install.png" alt="PHP Manager install">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Rewrite%20module.png" alt="Rewrite module">



<h2>Create a directory for PHP<h2>


<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/PHP%20Directory.png" alt="PHP Directory">

<h2>Extract the PHP folder into the created PHP directory<h2>


<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Extract%20PHP.png" alt="Extract PHP">

<h2>Install VC_redist.86.exe and MySQL<h2>


<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/VC%20Redist.png" alt="VC Redist">

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/My%20SQL.png" alt="MySQL">

<h2>Configure MySQL<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Configure%20MYSQL.png" alt="Configure MYSQL">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Configure%20MYSQL%202.png" alt="Configure MYSQL 2">


<h2>Register a new PHP version and choose the php-cgi.exe file<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Register%20PHP%201.png" alt="Register PHP 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Register%20PHP%202.png" alt="Register PHP 2">

<h2>Extract the os-Ticket-v1.15.8 into the inetpub\wwwroot folder<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Extract%20os-Ticket%20file%201.png" alt="Extract os-Ticket file 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Extract%20os-Ticket%20file%202.png" alt="Extract os-Ticket file 2">

<h2>Rename the upload folder in inetpub\wwwroot folder to "osTicket"<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Rename%20Upload%201.png" alt="Rename Upload 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Rename%20Upload%202.png" alt="Rename Upload 2">

<h2>Change the ost-sampleconfig.php file name to "ost-config.php"<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/ost-sample%20config%20change%201.png" alt="ost-sample config change 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/ost-sample%20config%20change%202.png" alt="ost-sample config change 2">

<h2>Enable required prerequisites for osTicket<h2>
  
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Enable%20Prereq%201.png" alt="Enable Prereq 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Enable%20Prereq%202.png" alt="Enable Prereq 2">

<h2>Give full edit access to osTicket<h2>
  
<img src="http://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Full%20edit%20Access.png" alt="Full edit Access">


<h2>Set up osTicket basic installation<h2> 
  
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Set%20up%20Basic%20Installation.png" alt="Set up Basic Installation">

  <h2>Download HeidiSQL and create a new session named "osTicket"<h2>

<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Heidi%20SQL%201.png" alt="Heidi SQL 1">
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/Heidi%20SQL%202.png" alt="Heidi SQL 2">

    
<h2>OsTicket is now fully installed and running!<h2>
<img src="https://raw.githubusercontent.com/JHeard0/osticket-prereqs/93c214a3ec0b582b8994b6631ebb976015ce573b/osTicket%20Prereq%20Finished.png" alt="osTicket Prereq Finished">

osTicket: Post-Installation Configuration (https://github.com/JHeard0/post-install-config)
