<h1> SEIM Prepared in Microsoft Azure Sentinel Map </h1>


<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connected it to a live virtual machine acting as a honey pot. I observed live attacks (RDP Brute Force) from all around the world. I then used a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>ipgeolocation.io<b>

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Walk-through:</h2>

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
Failed login test:  <br/>
<img src="https://i.imgur.com/iTX4X6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Event veiwer in virtual machine:  <br/>
<img src="https://i.imgur.com/Qkpcima.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Failed login in event viewer:  <br/>
<img src=https://i.imgur.com/rGnNK5q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The login data will be sent to API to create a custom log:  <br/>
<img src="https://i.imgur.com/jBWvsEC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Turn of firewall in virtual machine:  <br/>
<img src="https://i.imgur.com/AzlhMYB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In Powershell run custom script:  <br/>
<img src="https://i.imgur.com/IVIahFG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Script results generated in hidden file:  <br/>
<img src="https://i.imgur.com/IXwa5CZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Copy to notepad on home computer:  <br/>
<img src="https://i.imgur.com/gMhnqOw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create custom log:  <br/>
<img src="https://i.imgur.com/yTIENdD.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4GM44D2.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run custom log:  <br/>
<img src="https://i.imgur.com/nU7opVX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create and edit new workbook:  <br/>
<img src="https://i.imgur.com/BUWhFs5.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hjOjRnb.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run custom query:  <br/>
<img src="https://i.imgur.com/3wYVuKV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Initial Failed RDP Map generated:  <br/>
<img src="https://i.imgur.com/roEywkJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
72 hour Failed RDP Map:  <br/>
<img src="https://i.imgur.com/MBaEPsC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
