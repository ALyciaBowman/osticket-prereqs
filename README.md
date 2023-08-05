<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>


<h2>Description</h2>
This project consists of the prerequisites and installation of the open-source help desk ticketing system osTicket.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)
- MySQL
- Heidi SQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

  
  
<b> Create Virtual Machine in Azure </b>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/1a5d8e97-79d8-444b-8dd3-5115de02e687)

<b> Connect to Virtual Machine via Remote Desktop <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/6ebb61a2-a678-4cc4-a705-a081eeb84055)



<b> Install / Enable IIS in Windows with CGI and Common HTTP Features <b/>


![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/39e00511-5f36-48a8-9815-8090aba56943)

<b> Install PHP Manager for IIS <b/>


![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/be6f7fda-8797-4eb2-b32d-35766940babe)

<b> Install Rewrite Module <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/a9026cbc-9f75-4608-ac52-0c0ea0153973)

<b> Create the directory C:\PHP <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/e82cce03-22ab-4c7b-9af5-8d2e5409abdb)

<b> Download PHP 7.3.8 and unzip the contents into C:\PHP <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/07e2b9d5-611b-4b06-ade3-766dc8c83c52)

<b> Download and Install C++ Redistributable <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/5990c879-3d18-49f1-957e-7e1c61533aa0)

<b> Download and Install MySQL Server <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/12e25400-35cc-4511-92af-50f006e93fe4)

<b> Open IIS as an Admin and Register PHP from within IIS <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/87c4fb87-229a-4843-ab9b-be315c5b34c6)

<b> Install osTicket v1.15.8 -- Extract and copy “upload” folder to c:\inetpub\wwwroot <b/>


![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/c4131c8f-500b-4891-84ed-416e1f8a97c0)

<b> Enable extensions for osTicket in IIS: imap, intl, opcache <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/1a22de5c-3f7b-4cae-a151-91761750d134)


<b> Assign Permissions: ost-config.php 

Disable inheritance -> Remove All

New Permissions -> Everyone -> All <b/>


![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/a2a35560-e964-4880-b5e3-be227fc5c140)


![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/8723443c-9d63-47d4-8cd4-c386d173f193)

<b> Begin set up of osTicket in the browser  <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/9d664ed2-cb62-4adc-9296-fe4e4d1fe8c3)

<b> Install Heidi SQL <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/727c20e4-3219-40ee-81e9-79fbd402e50c)

<b> Create "osTicket" Database in HeidiSQL <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/cd1799ea-1e82-4fde-ac97-78e5729b9904)

<b> Continue Setting up osTicket in browser <b/>

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/f3f5cd1e-acb3-454d-bcef-1c023a606dd8)

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/93658f68-9660-4d40-9b5d-2d43c31eb75e)

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/a0ad3e84-1c50-4230-a4ac-e6c08b50fcce)

![image](https://github.com/ALyciaBowman/osticket-prereqs/assets/141197471/c3bd0de0-c16b-43b4-8cc3-8176fa21f910)




<br />
