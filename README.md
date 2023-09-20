
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
<img src="https://i.imgur.com/OO3yq1C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/DYpFH0H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
I proceeded to download and install the files from the google folder and unzip the contents of PHP into a folder I created on the C: drive. Then I registered PHP within IIS and restarted the server. This allowed me to download and connect to osTicket on the browser with "browse *80".
</p>
<br />

<p>
<img src="https://i.imgur.com/kmm1Ln8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, I needed to enable extensions for osTicket and assign permissions to ensure the efficiency on the browser. After clean up I was able to continue setting up osTicket in the browser.
</p>
<br />
