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
![Image Alt]([https://github.com/ShelShel3/SIEMLab/blob/5a451ea16c9ee93636686914dee65fd59f7431b5/Screenshot%202025-03-23%20194222.png]
<br />
<br />
Viewing Raw Logs on the Virtual Machine:  <br/>
 ![Image Alt](image_url)
<br />
<br />Creating Log Repository - Log Analytics Workspace: <br/>
 ![Image Alt](image_url)
<br />
<br />
Connecting our VM to Log Analytics Workspace:  <br/>
 ![Image Alt](image_url)
<br />
Querying Our Log Repository with KQL:  <br/>
 ![Image Alt](image_url)
<br />
<br />
Uploading our Geolocation Data to the SIEM  <br/>
 ![Image Alt](image_url)
<br />
<br />
Inspecting our Enriched Logs - We can see where the attackers are:  <br/>
 ![Image Alt](image_url)
<br />
<br />
Creating our Attack Map:  <br/>
  ![Image Alt](image_url)
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
