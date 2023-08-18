<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
Utilized Oracle Virtual Box to create a lab environment. Created a virtual machine with Windows Server 2019 to function as the Domain controller, and built a second virtual machine with Windows 10 to serve
as a client. Installed Active Directory, and a DHCP server on the Domain controller to serve 1000 mock users. The users were automatically generated using a PowerShell script. 
<br />

<h2>Objective</h2>
The purpose of this initiative was to enhance my knowledge of Active Directoy, as well as Windows Server, and PowerShell. This lab will also be the starting point for other future labs as I now have an environment in which I can learn more about cybersecurity and systems administration.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>
 
<h2>Program walk-through:</h2>

The domain controller was configured with two NIC cards. One NIC for internet access, and a second one for the internal networking (Netwrok Gateway, DNS, and DHCP).

Active Directory was installed on the Domain Controller (Windows 2019 machine). 
<img src="https://imgur.com/rMB77El.png" height="80%" width="80%"/>

A DHCP server was installed using a scope of IPs.
<img src="https://imgur.com/nP45N0A.png" height="80%" width="80%"/>


1003 users were created in Active Directory using a PowerShell script (Thanks to Josh Madakor)

<img src="https://imgur.com/EniZ4VU.png" height="80%" width="80%"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
