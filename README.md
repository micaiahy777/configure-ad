<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 6 26 07 AM" src="https://github.com/user-attachments/assets/0215afc6-6427-47c1-9ebb-4cc61b078349" />
</p>
<p>
In Microsoft Azure, I started to make a domain controller and a seperate client computer to later on log in with the fake clients I will be creating. 
</p>
<br />

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 6 42 34 AM" src="https://github.com/user-attachments/assets/05d85bab-4fc6-436d-bf2a-b68407ac83f2" />
</p>
<p>
With my one admin user I created (I called her Jane Doe to be simple), I can now run a script that will create users to simulate a company with around 1000 employees.
</p>
<br />

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 7 02 22 AM" src="https://github.com/user-attachments/assets/9c7b9bdf-8f13-4bb4-997b-2d3708f3823c" />
</p>
<p>
This script seen above is used in Microsoft Powershell. It created 1000 fake clients with pre set passwords. From here, I can now log onto the seperate client computer with any of these fake clients since they are apart of my domain.
</p>
<br />
