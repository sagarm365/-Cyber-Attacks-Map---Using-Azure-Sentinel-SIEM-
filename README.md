# Cyber-Attacks-Map---Using-Azure-Sentinel-SIEM

<h2>Description</h2>
Project consists of a creating a Sensitivity Label. 
 Configured Log Analytics Workspace in Azure to ingest custom logs containing geographic information (latitude, longitude, state/province, and country).
• Configured Custom Fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel.
• Configured Azure Sentinel (Microsoft's SIEM) Workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks.
<br/>

<h2>Environments Used </h2>

- <b>Microsoft Azure Trial </b> 
- <b>Remote Desktop Communication</b>

<h2>Prerequisites</h2>

- <b> Licenses: Microsoft Azure Trial or above</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1. Create Azure Subscription
2.	Create Virtual Machine
3.	Firewall turn off / allow all in firewall
4.	Create Log Analytics Workspace
5.	Enable gathering VM logs in Security Center
6. Connect Log Analytics to VM
7. Setup Azure Sentinel
8. Log into VM with Remote Desktop
9. Observe Event viewer Logs in VM
10. Turn of Windows Firewall on VM
11. Running a powershell script
12. Get Geolocation.io API Key
13  Run Script To get Geo Data from attackers
14. Create custom log in LAW to bring in our custom log
15. Create custom fields/extract fields from raw custom log data
16. Testing Extracts
17. Setup map in sentinel with Latitude and Longitude (or country)
18. Fixing Map plot sizes
19. Final check on map



<h3>Screenshots:</h3>

<p align="center">
Create Virtual Machine: <br/>
<img src="VM.png" height="50%" width="50%" />
<br/>
<img src="VM 1.png" height="50%" width="50%" />
<br />
<br />
Firewall turn off / allow all in firewall: <br/>
<img src="ALLOW ALL.png" height="50%" width="50%"/>
<br />
<br />
Create Log Analytics Workspace: <br/>
<img src="log analytics.png" height="50%" width="50%"/>
<br />
<br />
Enable gathering VM logs in Security Center: <br/>
<img src="Security center.png" height="65%" width="50%"/>
<br />
<img src="Security center 1.png" height="65%" width="50%"/>
<br />
Connect Log Analytics to VM: <br/>
<img src="connect log to vm.png" height="65%" width="50%"/>
<br />
<br />
Observe Event viewer Logs in VM: <br/>
<img src="observe event viewer.png" height="50%" width="50%"/>
<br />
<br />
Turn of Windows Firewall on VM: <br/>
<img src="turn of firewall.png" height="65%" width="50%"/>
<br />
<br />
Powershell script: <br/>
<img src="powershell script.png" height="65%" width="50%"/>
<br />
<br />
Get Geolocation.io API Key: <br/>
<img src="get geolocation.png" height="50%" width="50%"/>
<br />
<br />
Run Script To get Geo Data from attackers: <br/>
<img src="run script.png" height="65%" width="50%"/>
<br />
<br />
Create custom log in LAW to bring in our custom log: <br/>
<img src="create custom log.png" height="65%" width="50%"/>
<img src="create custom log 1.png" height="65%" width="50%"/>
<img src="create custom log 2.png" height="65%" width="50%"/>
<br />
<br />
Create custom fields/extract fields from raw custom log data: <br/>
<img src="extract.png" height="50%" width="50%"/>
<br />
<img src="extract1.png" height="50%" width="50%"/>
<br />
<img src="extract 2.png" height="50%" width="50%"/>
<br/>
<img src="extract 3.png" height="50%" width="50%"/>
Watermark: <br/>
 
<img src="add watermark.png" height="65%" width="50%"/>
<br />
<br />
Select Sensitivity info type: <br/>
<img src="sensitivity info types.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="50%" width="50%"/>
<br />
<br />




</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
