# Azure-Sentinel-With-Live-Attacks

This tutorial outlines the Set Up of setting up Azure Sentinel mnonitoring live attacks.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure Virtual Machines
- Microsoft Defender/ Mircosoft Sentinel 
- Windows 11
- Azure Storage 
- Azure Resource Group
- Azure Logs
- Azure SQL

Create a resource group

Create a log anlytics withing resource group

Create a VM > Make the VM Vulnerable by allowing everything to be open in the NSG (Create VM under resource group)

Add VM under Log Analytics 

Remote into VM

Go to ("https://ipgeolocation.io/") within VM and sign up 

Go to wf.msc and turn off all firewalls

Then open Windows Powershell ISE and run custom scrpit with free GEO IP location you received 

Observe failed logons and save some in file, upload file to log analytics > Tables > Save Workbook

Upload Workbook > Open Micorsoft Sentinel > Upload Workboook and select the view "Country" 

View Incoming attacks 


<h2>Deployment</h2>

<p align="center">
<img src="https://i.imgur.com/mtGtpC5.png" alt="Creation Of Resource Group"/>

</p>
<br />


<p align="center">
<img src="https://i.imgur.com/wXQ2E9s.png" alt="Creation Of Log Anlytics"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/fY6saLg.png" alt="Creation Of VM"/>

</p>
<br />


<p align="center">
<img src="https://i.imgur.com/jcCzVRI.png" alt="Remote into VM and get Free API Geo"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/La4ymmc.png" alt="After Adding geting free GEO IP Location, run custom Powershell scpit"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/limyQWr.png" alt="Save failed logons and upload them into workspace"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/Tf56FtU.png" alt="Upload saved workbook and create map"/>

</p>
<br />


# Go Here to get custom powershell code 
("https://github.com/joshmadakor1/Sentinel-Lab/tree/main")
