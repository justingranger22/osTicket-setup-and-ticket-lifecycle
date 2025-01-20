<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines after installation setup and ticket lifecycle




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1 Configuring Roles, Departments, Teams etc
- Step 2 Creating Different Types of SLA (Service Level Agreement) Tickets
- Step 3 Creating differnt Help Topics
- Step 4 Creating and Completing Tickets

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/0aaaccc7-a5c9-4365-935c-1a0b445976f6)
![image](https://github.com/user-attachments/assets/0468cd2d-566b-4daf-8d55-41b797bcfa20)

</p>
<p>
In order to configure osTicket roles, departments, etc you will need to start by clicking the admin panel in the top by your name, go to agents, roles is you want to add a new role that does not exist, departments for all types like support, tech, customer service, etc. Also make sure you delete maintenance or change the priority otherwise some tickets will randomly get assigned to this for no reason. Teams can be used for different classes of people (agents). Agents will allow you to create new users (if you want another admin besides yourself check the box at the bottom before you create them). You can also assign them to different departments, give permissions, allow certain access and also differnt teams by clicking the differnt tabs. Once you done everything you like just click create. If you want to create customers (users) click on agent panel, users, new and this allows to create customers that can submit tickets. Just try out a bunch of differnt things and learn how this program works since your job may have a differnt system but this is basically how most opperate.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/161c5efa-4d72-4924-af99-fba26c1ca0d5)

</p>
<p>
Now we can create different SLA (service level agreements). These are very important as it is basically a scale from emergency to normal issues. In other words you handle them depending on the level of needs. To create one click on admin panel, manage, SLA, add new SLA. Then fill out the name ( I used letters in this example but you can use anything you like, just remember which one is most to least important). Grace period is a short time frame given after a deadline during which the service provider can still meet their obligations without penalties. Think of it as a buffer zone where delays are forgiven, ensuring smooth operations even if something goes slightly off track. For instance, if the SLA states that a service must be completed within 24 hours, a grace period might extend this to 26 hours before any penalties apply. It's like getting a little extra time to hand in your homework without being late. The schedule outlines when certain services or tasks should be completed. Think of it as a timeline or calendar that specifies the deadlines and time frames for delivering services or resolving issues. For example, an SLA might state that customer support requests will be responded to within 2 hours and resolved within 24 hours. The final option or business hours means that you will try to resolve the issues during work hours only unlike the others where you work on them all day regardless since those are more time sensitive
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/0a64f231-0713-4e8b-b4d5-bbb7909a2d18)

</p>
<p>
In this example I've created a few differnt types of ticket help topics so when customers submit a ticket it can be categorized into a topic instead of just all of them in a generic or general topic. To do this just click on the admin panel, manage, help topics and add new topic. Here you can name the topic, choose the parent topic (where it goes), and by clicking the new ticket options you can change the priority, assign a SLA and even auto assign to a certain team or agent. 
</p>
<br />

![image](https://github.com/user-attachments/assets/a48be0dc-133c-4818-9545-9cca732f98c3)
![image](https://github.com/user-attachments/assets/3fe0c57f-2db5-4b76-bd53-fa32d61349bf)
Here you will learn how to submit, check and resolve tickets. To get started go to the other tab that is labeled my help desk or whatever you named it and click submit new ticket (this is a differnt site than the control panel we just used). Fill out the information (red asterisk being required information) and click create ticket. 

![image](https://github.com/user-attachments/assets/6d1c0000-0e5d-4ba4-907d-da28910602b1)
![image](https://github.com/user-attachments/assets/479f3560-ddc8-4f54-9caf-8d6ef3f08a83)

In order to look at and resolve tickets log off the admin and log into an agent. Once logged in you should see the ticket on the dashboard. Click on it and you will notice a thread has started. This is how you keep in contact with your customer without going back and forth with emails. You can reply to the customer just to acknowledge that you have received the ticket. Once you figure out the solution reply back to them in a friendly manner and on the bottom there is a status drop bar labeled ticket status to either resolve the ticket or by default keep it open. If you click post reply when the ticket status is resolved you will NO longer see the ticket on the dashboard. If you want to check it click on the closed ticket tab and it will show you all the tickets that have been resolved or closed for that time frame you choose. Hope this helps you to understand how these systems work since you will be spending a majority of your days solving all kinds of issues. Just remember even if you can't resolve it right away, just keep in contact with the customer and be honest with them so they know that you and your team are working on the solution. It is better than ignoring them and having an angry customer
