# osticket-prereqs
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

- Create an Azure VM
- Install IIS with CGI
- Install PHP Manager
- Install Rewrite Module
- Install MySQL
- 
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/8PL3JFl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and Unzip Files: Get the osTicket-Installation-Files.zipand unzip it on your desktop.
Install IIS with CGI: Enable IIS and CGI in Windows.
Install PHP Manager: From the installation files, install PHP Manager for IIS.
Install Rewrite Module: Install the Rewrite Module from the installation files.
Create PHP Directory: Create a directory at C:\PHP.
Unzip PHP: Unzip PHP 7.3.8 into the C:\PHP folder.
Install VC_redist: Install the VC_redist.x86.exe from the installation files.
Install MySQL: Install MySQL 5.5.62 and configure it  
</p>
<br />

<p>
<img src="https://i.imgur.com/FutvlVL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS: Run IIS as an Admin.
Register PHP in IIS: Use PHP Manager to register C:\PHP\php-cgi.exe.
Reload IIS: Stop and start the IIS server.
Install osTicket: Unzip osTicket v1.15.8 and move the upload folder to C:\inetpub\wwwroot, then rename it to osTicket.
Reload IIS: Stop and start the IIS server again.
Browse osTicket: Go to sites -> Default -> osTicket and click "Browse *:80".
Enable PHP Extensions: Enable php_imap.dll, php_intl.dll, and php_opcache.dll in PHP Manager.
Rename Config File: Rename ost-sampleconfig.php to ost-config.php in the include directory.  
</p>
<br />

<p>
<img src="https://i.imgur.com/GrKlxZ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Set Permissions: Disable inheritance and set new permissions for ost-config.php.
Continue Setup in Browser: Complete the setup in the browser, providing helpdesk name and default email.
nstall HeidiSQL: Install HeidiSQL and create a new session with root/root.
Create Database: Create a database named osTicket.
Finish Setup: Complete the osTicket setup in the browser with the database details and click "Install Now!".
Clean Up: Delete the setup directory and set ost-config.php to read-only.  
</p>
<br />
