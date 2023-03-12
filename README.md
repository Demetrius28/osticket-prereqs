<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)



<h2>Installation Steps</h2>

<h2> Step 1: Enable IIS in Windows with CGI
<img src="https://i.imgur.com/0HVTvY5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Step 1: Enable IIS in Windows with CGI</h3>

- Right click on the windows icon> choose "Run" 
- Open "Control Panel" 
- Click "Programs"
- Choose "Turn Windows Features on or Off"
- Scroll down to turn ON "Internet Information Services" by filling in the selection box.
- click the boxes to expand the following: "Internet Information Services"; "World Wide Web Services"; "Application Development Features"
- Click to check the box next to "CGI" to enable it
- Click "OK"
</p>
<br />
<h2>Step 2: Access Prerequisite Installation Files</h2>

- Open Microsoft Edge from within the Remote Desktop to access the internet img#1
(On first time opening Edge, turn off any personalization or marketing options that pop up)

- From within Edge, Access the installation files for all prerequisite installations and osTicket Software installation by copying this file into the Edge browser: [Link to Files](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6) 
</p>
<br />

<h2>Step 3: Install PHP Manager</h2>

- From the Installation files, Download and install PHP Manager for IIS (PHPMangerForLLS_V1.5.0msl)
(If you receive an error "this file type might be dangerous", click to "download anyway")
- After file has downloaded, choose "Open file"; click "next"; "I Agree"; "Next"; "Close"
</p>
<br /><hr>
<h2>Step 4: Install Rewrite Module</h2>

- From the Installation Files, Download and Install the "Rewrite Module" (rewrite_amd64_en-US.msl)
(If you receive an error "this file type might be dangerous", click to "download anyway")
- After file has downloaded, choose "Open file"; accept license agreement; Install; Finish
</p>
<br />
<hr>
<p>
<h2>Step 5: Create PHP Directory</h2>
<img src="https://i.imgur.com/hmXl0g8.png" height="80%" width="80%" alt="Enable IIS"/>
</p>
<p>
<h3>Step 5: Create PHP Directory</h3>

- Click on the "File Explorer" icon
- Choose "This PC"
- Type or Choose "C:"
- Right Click to choose to add a "New" "Folder"
- Name this folder "PHP"

</p>
<br /><hr>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is important to take care of the patient, to be followed by the doctor, but it is a time of great pain and suffering. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the reprimand in the pleasure he wants to be a hair from the pain in the hope that there is no breeding.
</p>
<br />
<p>
<h3>Step 6: Install PHP7.3.8</h3>

- From the Installation Files, download PHP7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) 
- Unzip contents into the new PHP folder  (C:\PHP)
  - Click to "Open File" from the downloads
  - "Extract All"
  - Select a destination, by typing "C:\PHP" to place it into the new C:\PHP folder.
  - "Select Folder"
  - "Extract"
</p>
<br />
<hr>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
