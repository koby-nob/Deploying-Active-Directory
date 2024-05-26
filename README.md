-  <b>Microsoft Azure</b>
    - [Deploying Active Directory Domain Services Within Micrsoft Azure VMs]
    - This project outlines the steps and process for installing Active Directory on Windows Server.


 <h2>Environments and Technologies Used</h2>

    - Microsoft Azure (Virtual Machines named: DC-1 & Client-1)
    - Remote Desktop

<h2>Operating System Use </h2>

    - Windows 10 Pro  
    - Windows Server 2022 Datacenter: Azure Edition -x64


 ![DC_1_Admin](https://github.com/koby-nob/Deploying-Active-Directory/assets/166937258/bd59faf0-3b04-4ab8-a530-8b975dbad1cb)


<h2>Installation Steps</h2>

- This project will display the deployment section of Active Directory after creating DC-1 & Client-1 VM's in Microsoft Azure

<p>
<img src="https://i.imgur.com/oRrNsje.png"
</p>
<p>

    - Click the START button to open the Server Manager or double click the Server Manager icon from Windows desketop screen.
    - Once the Server Manager is opened, > select Dashboard > then click on "Add roles and features" to start the install process.

    
<p>
<img src="https://i.imgur.com/is7DETm.png"   
</p>
<p>

    - Click on Next button from the "Add Roles and Features Wizard" screen move to the next section

<p>
<img src="https://i.imgur.com/cI1Mt2J.png"
</p>
<p>

    - Select Role-based or feature-based installation for the purpose of this project
    
<p>
<img src="https://i.imgur.com/DmkvEDu.png"
</p>
<p>

    - Check the "Active Directory Domain Services box, then click on next button

<p>
<img src="https://i.imgur.com/ntcpmFB.png"
</p>
<p> 
    
    - Wait few seconds for installation to be completed and click on the close button to move to deployment configuration screen

<p>
<img src="https://i.imgur.com/QRx5C5V.png"
</p>
<p> 
    
    - Select the "Add domain contoller to an existing domain" for deployment operation
    - In the Domain box, type: MYDOMAIN.COM for the purpose of this project
    

<p>
<img src="https://i.imgur.com/IKAHWml.png"
</p>
<p>

    - After the installation is completed, go to the Server Manager > Dashboard  to confirm AD DS is showing up. This will indicate Active Directory has been installed. 


