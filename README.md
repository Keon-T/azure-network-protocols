<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Active directory
- Remote desktop
- Security group


<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/EFwxtwO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open remote desktop log in as DC-1 as your domain admin account and create sample file shares with various permissions</p>
<br />

<p>
<img src="https://i.imgur.com/2HMSh0Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>Create "accountants" security group, to DC-1 in active directory set following permissions in accounting folder created 

<br />

<p>
<img src="https://i.imgur.com/ZJsa54u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>On DC-1 make following user a member of the "accountants" security group
<br />
