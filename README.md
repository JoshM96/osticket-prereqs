<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
In this lab I installed the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Created a Windows 10 Virtual Machine in Microsoft Azure
- Installed / Enabled IIS in Windows with CGI, common HTTP features, and IIS management console.
 Downloaded / installed PHP Manager and PHP 7.3.8
- Installed Microsoft Visual C++ Redistributable
- Installed and configured a MySQL 5.5.62 server isntance.
- Registered PHP from within IIS 

<h2>Installation Steps</h2>

<p>
 After downloading the latest version of osTicket, I extracted the "Upload" folder from C:\Users\labuser\Downloads\osTicket-v1.15.8.zip to c:\inetpub\wwwroot
 </p>
<img src="https://i.imgur.com/kP6Y3K5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/AIbcpzq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
 After opening osTicket from IIS I enabled some extra extensions from PHP Manager to increase the functionality of this osTicket instance.
</p>
<img src="https://i.imgur.com/8TAXRmf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XjP76EZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
 From here I configured the basic system settings and created the primary administrator account.
</p>
<img src="https://i.imgur.com/qOL8K0H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
 Before filling out the database settings, I created a new database for osTicket using HeidiSQL
</p>
<img src="https://i.imgur.com/hDzxNiD.png"80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/oKbHsZ5.png"80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/LzGvZ4t.png" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
 After clicking "Install Now" osTicket was successfully installed!
</p>
<img src="https://i.imgur.com/V5k8ioU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
