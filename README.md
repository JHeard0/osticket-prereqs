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

<img src="https://i.imgur.com/NYIKImI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<h2>Before proceeding with any downloads, enable CGI in IIS <h2> 

<img src="https://i.imgur.com/Zk0SPiY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Return to the os-Ticket installation files folder, then install PHP Manager and the rewrite module<h2>
  
<img src="https://i.imgur.com/Kxg1xX4.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/YjEUrye.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<h2>Create a directory for PHP<h2>


<img src="https://i.imgur.com/jnLjArY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Extract the PHP folder into the created PHP directory<h2>


<img src="https://i.imgur.com/PsUpivl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Install VC_redist.86.exe and MySQL<h2>


<img src="https://i.imgur.com/KJ3E86D.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/7NmsrYb.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> 
<h2>Configure MySQL<h2>


<img src="https://i.imgur.com//rDWcjZm.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/v40USMN.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<h2>Register a new PHP version and choose the php-cgi.exe file<h2>

<img src="https://i.imgur.com/H2PMSga.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/04NvY46.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<h2>Extract the os-Ticket-v1.15.8 into the inetpub\wwwroot folder<h2>

<img src="https://i.imgur.com/v1vg2WK.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/iO6VfUU.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<h2>Rename the upload folder in inetpub\wwwroot folder to "osTicket"<h2>


<img src="https://i.imgur.com/66ur5Dy.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/n6TaAMQ.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<h2>Change the ost-sampleconfig.php file name to "ost-config.php"<h2>


<img src="https://i.imgur.com/X2hvpMX.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/tFEhWZD.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>




<h2>Enable required prerequisites for osTicket<h2>
<img src="https://i.imgur.com/Sl1OEym.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0hwDHUJ.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>




<h2>Give full edit access to osTicket<h2>
<img src="https://i.imgur.com/UIy6Kgu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Set up osTicket basic installation<h2> 
<img src="https://i.imgur.com/FR4xrsG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <h2>Download HeidiSQL and create a new session named "osTicket"<h2>
<img src="https://i.imgur.com/pDG3cTA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/z1zzcKO.png" height="40%" width="40%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/QAiiz18.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    
<h2>OsTicket is now fully installed and running!<h2>
<img src="https://i.imgur.com/6u3JRYP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

osTicket: Post-Installation Configuration (https://github.com/JHeard0/post-install-config)
