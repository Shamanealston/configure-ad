
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>


![Image 8-5-24 at 10 44 AM](https://github.com/user-attachments/assets/9835f02b-3192-466b-97b6-60e5f7cd8d35)

</p>
<p>
In this screenshot, I chaged the "Domain Controller" virtual machine's NIC Private IP address to static so the IP address won't ever change regardless of any external factors. 


![image](https://github.com/user-attachments/assets/9640cb2b-cb10-4049-859a-3ec6599e6824)



![image](https://github.com/user-attachments/assets/40f54284-caef-4a3a-9f52-092421fcd76c)


In the first screenshot shows that I have created two virtual machines in Azure; one being the Domain Controller and the other one named Client 1 which is essentially the desktop of a domain user that I will generate later. The second one shows that I have connected to both virtual machines via remote desktop by using thier IP addresses. I displayed their hostnames using the command prompt app.


![image](https://github.com/user-attachments/assets/6db4b9b3-c9d7-482a-b8bc-2a6e3be223dd)


![image](https://github.com/user-attachments/assets/d4b98a37-3061-4f23-876b-7ec7cfeb6430)


![image](https://github.com/user-attachments/assets/e4ede234-67b9-4221-90a2-339c0db1630b)


![image](https://github.com/user-attachments/assets/e4791bb4-d89d-44df-a177-d62820e9be6d)

![image](https://github.com/user-attachments/assets/acbf8cc1-ac6e-4f90-9c2f-5915b983f39c)


![image](https://github.com/user-attachments/assets/0b01bcbd-5145-4f76-9e8d-cd3e9edb92b2)


![image](https://github.com/user-attachments/assets/2967e0ee-2b1a-4f2c-8ecc-f88a773e1ab5)


![image](https://github.com/user-attachments/assets/19f75846-266b-49c1-aaa7-51cc9ed32388)

![image](https://github.com/user-attachments/assets/189caba9-8bb1-4331-9af8-18d4f43271d2)


![image](https://github.com/user-attachments/assets/716fe5bf-6d93-4e49-9c44-f7b8771036db)



