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

![image_alt](https://github.com/ShelShel3/SIEMLab/blob/227061c9ff00794799d30c55d55caf620a5e613f/Screenshot%202025-03-23%20194222.jpg)

<br />
<br />
<p align="center">
Create Virtual Machine:  <br/>

 ![Image Alt](https://github.com/ShelShel3/SIEMLab/blob/5f2c69ec4b5d4c38155bbf8f563ee58fe84e44c6/Screenshot%202025-03-23%20194524.jpg)

<br />
<br />
<p align="center">
Creating Log Repository - Log Analytics Workspace: <br/>

 ![Image Alt](https://github.com/ShelShel3/SIEMLab/blob/94da3b1b7a409f7877715baeae4b873671c1e063/Screenshot%202025-03-24%20172554.jpg)

<br />
<br />
<p align="center">
Connecting our VM to Log Analytics Workspace:  <br/>

 ![Image Alt](https://github.com/ShelShel3/SIEMLab/blob/7d74c040e88ea9820934923bb2c801865e8c725d/Screenshot%202025-03-24%20172629.jpg)
<br />
<br />
<p align="center">
 Querying Our Log Repository with KQL:  <br/>

 ![Image Alt](https://github.com/ShelShel3/SIEMLab/blob/1575a747df5154087cff55ce9b05cf973f3801dc/Screenshot%202025-03-24%20172747.jpg)

<br />
<br />
<p align="center">
 Uploading our Geolocation Data to the SIEM  <br/>

 ![Image Alt](image_url)

<br />
<br />
<p align="center">
 Inspecting our Enriched Logs - We can see where the attackers are:  <br/>

 ![Image Alt](image_url)

<br />
<br />
<p align="center">
Creating our Attack Map:  <br/>
 
  ![Image Alt](image_url)

<br />
<br />
<p align="center">
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
