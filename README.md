<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

  ![Screenshot 2024-09-03 130554](https://github.com/user-attachments/assets/13e5a7f7-b9b1-41df-aeb8-19fba23916fc)

![Screenshot 2024-09-03 120258](https://github.com/user-attachments/assets/449ca518-ff33-43c4-9182-f89690e81075)

![Screenshot 2024-09-03 120639](https://github.com/user-attachments/assets/b6b82542-0024-48fd-9194-63d6a3b15e9e)

![Screenshot 2024-09-03 120820](https://github.com/user-attachments/assets/e9e90314-3d03-4f84-98b9-f74249862735)

</p>
<p>
In the images above, I configured Roles, Departments, and Teams to begin the workflow. 

After creating these roles, I updated Agents and Users to have the corresponding permissions on their profiles.
</p>
<br />

<p>

  ![Screenshot 2024-09-03 121030](https://github.com/user-attachments/assets/d33c0a81-109a-4d45-8dcb-f8830baafa76)

  ![Screenshot 2024-09-03 121104](https://github.com/user-attachments/assets/6e049918-2865-47f6-890f-08e90170fb24)

![Screenshot 2024-09-03 121144](https://github.com/user-attachments/assets/197d65bf-4112-430f-972e-408eefc51721)


</p>
<p>
In this portion, I reviewed and configured the SLA expectation by using the respective tiers below:
    
    - SEV-A (1 hour, 24/7) 
    - SEV-B (4 hours, 24/7)
    - SEV-C (8 hours, business hours)
</p>
<br />

<p>

  ![Screenshot 2024-09-03 121354](https://github.com/user-attachments/assets/83654a49-0b32-4175-b686-dcd6078d785f)

![Screenshot 2024-09-03 121607](https://github.com/user-attachments/assets/a504f394-797c-4962-be53-f7acc24f308d)


![Screenshot 2024-09-03 121451](https://github.com/user-attachments/assets/2203f017-48cb-4295-8271-846df0df04bb)

![Screenshot 2024-09-03 121511](https://github.com/user-attachments/assets/e7be6360-3554-4fe4-b059-3ad825d9032f)


</p>
<p>
Finally, I updated the Help topics to ensure we had a baseline to help users with their tickets. These topics are the following:
  
    - Business Critical Outage
    - Password Reset
    - Personal Computer Issues
    - Equipment Request
</p>
<br />
