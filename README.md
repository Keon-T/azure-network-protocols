<p align="center">
</p>

Group policy and Managing Accounts


<h2>Environments and Technologies Used</h2>

Administration Windows Powershell

Active directory users and computers 
- Microsoft Azure (Virtual Machines/Computer)


<h2>Operating Systems Used </h2>
- Azure
- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- CHATGPT
- Active directory
  


<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/Himz3s0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After logging into (dc-1) chose a random user account you created then configure group policy to lockout the account after 5 attempts so you can lock the account to observe it with active directory and unlock it then reset to password to login with correct password <br />

<p>
<img src="https://i.imgur.com/BtHn9Ki.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enabling and disabling is with the same account from previously use active directory to disable it and wait for the attempt login error message then re-enable the account then proceed to login with it 
<br />

<p>
<img src="https://i.imgur.com/ZJsa54u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observing Logs
- Observe the logs in the Domain Controller
- Observe the logs on the client Machine
<br />
