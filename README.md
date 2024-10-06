<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### (https://youtu.be/WRr7XhbUlJg?si=KSY_BcOhlakY9-4b)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure
- Virtual Machine
- OsTicket Installation Files
  
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>Step 1:Connect to your Virtual Machine with Remote Desktop
<br />Starts with you creating a azure account
and of course resource groups as well.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>Step 2: Install and Enable Internet Information Services (IIS) in Windows

<br /> At the bottom left, search for Control Panel

<br /> Underneath Programs, select Uninstall a Program

<br /> On the left side of the screen, select Turn Windows Features On or Off

<br /> Select internet information Services (IIS), and select OK

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p> Step 3: Download, Install, and Open the Web Platform Installer

<br /> OsTicket Installation Files
-Download Web Platform Installer> select Download Anyway> at the top right, select Open file
-Follow the prompt to install Web Platform Installer
- Open the Web Platform Installer

  Step 4: Install OsTicket v1.15.8
  <br /> Download OsTicket (download from within lab files)

  <br /> Right-click on the file and select Extract All
  -Open the new OsTicket folder
  <br /> Copy the upload folder into C:\inetpub\wwwroot
  <br /> Rename Upload to osTicket
