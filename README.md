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
<img src="<blockquote class="imgur-embed-pub" lang="en" data-id="a/0yVwRZU" data-context="false" ><a href="//imgur.com/a/0yVwRZU"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>" alt="Creation Of Resource Group"/>

</p>
<br />



