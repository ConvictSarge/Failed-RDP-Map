<h1> Failed RDP Map from Azure Honeypot</h1>

 ### [YouTube Demonstration](https://youtu.be/XXXXXXXXXXX)

<h2>Description</h2>
This project consisted of creating a honeypot inside of Microsoft Azure. After creation, all firewall rules were turned off to allow all incoming traffic. A PowerShell script was utilized to transfer data to a third party API that geolocated the attackers IP address and inserted into the Log Analytics. A workbook in Azure was created from the Log Analytics to display the data on a world map.  The project was run for 7 days. *DISCLAIMER: The free API integration only allows for 1000 logged hits per 24 hour block.*

<h2>Languages and Utilities</h2>

- <b>Azure</b>
- <b>Sentinel (SIEM)</b>
- <b>PowerShell</b>
- <b>Third-Party API (ipgeolocation.io)

<h2>Environments Used</h2>

- <b>Windows 10</b> (22H2)

<h2>Program Walk-through</h2>
<p align="center">
Inital map shortly after set up: <br/>
<img src="https://i.imgur.com/12MOVhp.png" height="80%" width="80%" alt="Initial aftersetup"/>
<br/>
<br/>
Logging of an attack from The Netherlands using randomizations of "Admin", "Administrator", and "User" usernames in RDP, most likely a dictionary attack:<br/>
<img src="https://imgur.com/BhkwVN9.png" height="80%" width="80%" alt="Netherlands ATTAKS!"/>
<br/>
<br/>
Live screenshot of the attacks from The Netherlands. NOTE: The error is a flag from the third-party API, I was over the limit of 1000 in less than 2 hours, but it appears they kept logging the events.<br/>
<img src="https://imgur.com/0y5XKLY.png" height="80%" width="80%" alt="Netherlands Attacks realtime"/>
<br/>
<br/> 
It seems someone in "Washington, Virgina" started to show some interest.
<img src="https://imgur.com/GU0SAjx.png" height="80%" width="80%" alt="Washington, VA"/>
<br/>
<br/> 
After approximately 24 hours.<br/>
<img src="https://imgur.com/bP3auO3.png" height="80%" width="80%" alt="24 Hours in"/>
<br/>
<br/> 
</p>
