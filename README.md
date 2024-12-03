# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



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
Create an Azure VM: Set up a Windows 10 VM with 4 vCPUs.

Log in via Remote Desktop: Use the credentials provided to log in.

Download and Unzip Files: Download osTicket-Installation-Files.zip and unzip it on the desktop.

Install IIS with CGI: Enable IIS and CGI in Windows.

Install PHP Manager and Rewrite Module: From the unzipped folder, install PHP Manager for IIS and the Rewrite Module.

Set Up PHP: Create a directory C:\PHP and unzip PHP 7.3.8 into it. Install VC_redist.x86.exe.  
</p>
<br />

<p>
<img src="https://i.imgur.com/FutvlVL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create an Azure VM: Set up a Windows 10 VM with 4 vCPUs.

Log in via Remote Desktop: Use the credentials provided to log in.

Download and Unzip Files: Download osTicket-Installation-Files.zip and unzip it on the desktop.

Install IIS with CGI: Enable IIS and CGI in Windows.

Install PHP Manager and Rewrite Module: From the unzipped folder, install PHP Manager for IIS and the Rewrite Module.

Set Up PHP: Create a directory C:\PHP and unzip PHP 7.3.8 into it. Install VC_redist.x86.exe. 
</p>
<br />

<p>
<img src="https://i.imgur.com/GrKlxZ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Set Up Database: Use HeidiSQL to create a database called osTicket.

Finalize Installation: Complete the setup in the browser and clean up by deleting the setup folder and setting permissions to read-only for ost-config.php.  
</p>
<br />
