
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

- Virtual Machine in Azure
- Installation of osticket dependency files
- Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/VFprPpN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a resource group in Azure, then created a Windows 10 virual machine with 2-4 Virtual CPUs within the resource group. This also required me to set a password for remote desktop connection. 
</p>
<br />

<p>
<img src="https://i.imgur.com/kvm1DGV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/a41jkgE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I used a provided list of osTicket prerequsite files to download onto the virtual machine. To prevent errors while downloading I enabled CGI and Common HTTP Features and IIS Management Console from the control panel-enable programs settings. 
</p>
<br />

<p>
<img src="https://i.imgur.com/R5oIGx0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/9SxTV4o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I proceeded to download the files from the google folder and unzip the contents of PHP into a folder I created on the C: drive. Other downloaded files just needed to be installed and configured.  
</p>
<br />
