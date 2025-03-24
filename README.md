<h1>Home SIEM Lab</h1>



<h2>Description</h2>
For this project, I set up a basic home SOC in Azure from scratch. Using a free Azure subscription, I created a virtual machine (VM), opened it to the internet as a honeypot, and forwarded logs to a central repository. I then integrated Microsoft Sentinel to analyze real-world attack data.
<br />


<h2>Environments Used </h2>

- <b>Windows 11</b> 
- <b>Microsoft Azure</b> 

<h2>Project walk-through:</h2>

<p align="center">
Create Free Azure Subscription: <br/>
<img src="https://]https://imgur.com/a/bq9xWPM" height="80%" width="80%" alt="Subscription"/>
<br />
<br />
Viewing Raw Logs on the Virtual Machine:  <br/>
<img src="[https://i.imgur.com/tcTyMUE.png](https://imgur.com/a/v8ouJHs)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Creating Log Repository - Log Analytics Workspace: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connecting our VM to Log Analytics Workspace:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Querying Our Log Repository with KQL:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Uploading our Geolocation Data to the SIEM  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inspecting our Enriched Logs - We can see where the attackers are:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating our Attack Map:  <br/>
 <img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
