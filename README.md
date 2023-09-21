<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this project we're goiung to walk through how to create an active directory home lab Environment using VM ware workstation pro. Configure and running this lab will definitely help develop your understanding of how active directory and windows network works, So i'd highly recommend running through i a couple times, ask questions where stuff is unclear, and eventually try to build it on your own. Please let me know if you have any questions!
<br />


<h2>Languages and Utilities Used</h2>

- <b>PCommand prompt (CMD)</b> 
- <b>VMware workstation pro</b>
- <b>Domain Name System(DNS)</b>
- <b>Dynamic Host Configuration Protocol(DHCP)</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows server 2016</b> 

<h2>Program walk-through:</h2>

<p align="center">
While installing Windows server give Administrator a Password: <br/>
<img src="https://i.imgur.com/TM8xdWB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install the DHCP role from add roles and features:  <br/>
<img src="https://i.imgur.com/TtARKYl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a new scope: <br/>
<img src="https://i.imgur.com/HTDEAmy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP scope configuration:  <br/>
<img src="https://i.imgur.com/oAlSMsH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP scope configuration:  <br/>
<img src="https://i.imgur.com/vwUP5pv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP scope configuration:  <br/>
<img src="https://i.imgur.com/fDImKNT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Activate the scope:  <br/>
<img src="https://i.imgur.com/PA5lTsW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
The client machine is able to get the IP from windows server:  <br/>
<img src="https://i.imgur.com/8QKPx6X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now install the ADDS Role from add roles and features:  <br/>
<img src="https://i.imgur.com/Vgnluif.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Promote the server to Domain controler:  <br/>
<img src="https://i.imgur.com/873zxbN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Give FQDN for domain controler:  <br/>
<img src="https://i.imgur.com/Eu03Z6D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After resatart the screen should look like this:  <br/>
<img src="https://i.imgur.com/iRRrQsx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For client system go to > properties > advance system settings > change name > enter domain name:  <br/>
<img src="https://i.imgur.com/QWuT1lh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
