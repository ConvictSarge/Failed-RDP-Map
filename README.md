<h1> Failed RDP Map from Azure Honeypot</h1>

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

