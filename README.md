<h1> SEIM Prepared in Microsoft Azure Sentinel Map </h1>


<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connected it to a live virtual machine acting as a honey pot. I observed live attacks (RDP Brute Force) from all around the world. I then used a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>ipgeolocation.io<b>

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a Virtual Machine: <br/>
<img src="https://i.imgur.com/lBcaxq4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create the Log analytics:  <br/>
<img src="https://i.imgur.com/Y7jJKdC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose your defender plan: <br/>
<img src="https://i.imgur.com/JXbTZkG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable data collection:  <br/>
<img src="https://i.imgur.com/75WNhJV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect to Virtual Machine:  <br/>
<img src="https://i.imgur.com/6DKrdVB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access Virtual Machine:  <br/>
<img src="https://i.imgur.com/LwtxCBv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Failed log in test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
