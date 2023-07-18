<h1>Azure Sentinel Tutorial map with Live Cyber Attacks</h1>

 ### [Medium Blog](https://medium.com/@adityaahuja.work/azure-sentinel-tutorial-map-with-live-cyber-attacks-siem-93f2dbb0428e)

<h2>Description</h2>
Project consists of setting up Azure Sentinel which is a SIEM(Security information and event management).A vulnerable virtual machine will be setup(RDP enabled) which is prone to attackers from all over the world.
The failed login attempts will be extracted from the event viewer and custom logs will be created.The logs will contain geolocation of attackers' ip addresses and these locations will be plotted on a world map using Azure
Sentinel.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b> 
- <b>Powershell</b>
- <b>Remote Desktop Protocol</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>PowerShell Script</h2>

- <b>Log Collection</b>
<h2>Sentinel walk-through:</h2>

<p align="center">
Creating log analytics workspace: <br/>
<img src="https://i.imgur.com/zgg8FJR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connecting VM to the log analytics workspace:<br/>
<img src="https://i.imgur.com/WkBrJO8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Customisation of Firewall rules: <br/>
<img src="https://i.imgur.com/oIRIF02.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Failed Login RDP attemp:  <br/>
<img src="https://i.imgur.com/DMELbts.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom log creation:  <br/>
<img src="https://i.imgur.com/rGIC2f6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Plotted Map  <br/>
<img src="https://i.imgur.com/GAvfGGu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
