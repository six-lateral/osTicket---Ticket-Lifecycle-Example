# osTicket: Ticket Resolution and Troubleshooting

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Objectives</h1>

<b>Create Sample Tickets</b>

  - In order to practice resolving tickets we must first create them

<b>Practicing Ticket Resolution</b>

  - Understanding the complete lifecycle of a ticket within osTicket

<b>Using Efficient Troubleshooting Techniques</b>

  - Implement troubleshooting techniques for common IT issues, ensuring clear and concise problem solving

<b>Enhancing User Satisfaction</b>

 - Providing timely and effective support, fostering a positive experience and minimizing downtime for end-users

<b>Building a Knowledge Base</b>

  - As we resolve tickets we will also be building out a comprehensive knowledge base by documenting common issues and their resolutions, improving the experience for both the support teams and end-users


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)
- MySQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Prerequisites</h2>

- [osTicket - Prerequisites and Installation](https://github.com/ben-trainer/osTicket-prerequisites)
- [osTicket - Post-Install Configurations](https://github.com/ben-trainer/osTicket-post-install-cfg)


<h1>Resolving Tickets in osTicket</h1>

In this lab I go through the lifecycle of a ticket from the intake to resolution within the open-source help desk ticketing system osTicket. We will be creating, managing, and troubleshooting our own tickets for the purpose of demonstration. <br />

<h2>Lifecycle Stages</h2>

First we must create our tickets which can be done by visiting the “localhost/osTicket/index” on our web browser. Select open ticket and fill out the request.

<p>
<img src="https://i.imgur.com/HC8kKV0.png" height="80%" width="80%" alt="Ticket Steps"/>

<p><strong>.</strong></p>
<p><strong>.</strong></p>

Once we have created our sample tickets they will appear in our tickets tab within our admin panel. Here I created a variety of tickets which need to be categorized based on priority and assign them to the correct professional.



<img src="https://i.imgur.com/GDQ6vLa.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p>
Jane Doe worked the ticket and assigned it to the System Administrator department, also setting the SLA level, and adjusted the Priority Level. The customers are also able to select the Help Topic to help the IT professionals categorize tickets better.

</p>
<br />

<p>
<img src="https://i.imgur.com/gtw5Nok.png" height="80%" width="80%" alt="Ticket Steps"/>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
This is what the ticket looks like on the System Administrator’s side, logged in as Benjamin Bravo.
  
<img src="https://i.imgur.com/cACxLCP.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
Here I resolve the issue, closing the ticket, and you can see the updated ticket here.

</p>
<br />

<p>
<img src="https://i.imgur.com/j29yfjo.png" height="80%" width="80%" alt="Ticket Steps"/>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
Jane Doe was able to work the ticket and assign it to herself, resolving the issue promptly.

<img src="https://i.imgur.com/H0vCre3.png" height="80%" width="80%" alt="Ticket Steps"/>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
Jane Doe reached out to John with a warm hand off. Now John Doe (me) received the ticket directly into his ticket queue. Where John Doe (me) was able to resolve it promptly.

<img src="https://i.imgur.com/Tfk912Y.png" height="80%" width="80%" alt="Ticket Steps"/>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

The result from the agent's on the Agent Panel.


<img src="https://i.imgur.com/0t58zTx.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>
<p>


</p>
<br />

<h2>Lessons Learned</h2>

I learned of the use of SLAs in help desk positions, which can change the priority of a ticket, outside of its own categorized priority to uphold a specific company’s quotas. Building out a database like this from scratch helped me understand how valuable documentation is within a helpdesk environment regarding departments and who to assign tickets to. Ensuring concise clear communication between each other.


Strong communication is critical while resolving tickets, being clear and concise go a long way for you coworkers and customers. Tickets are coming in with very different or similar issues and should be assigned to the appropriate person or team. Jane was able to manage and resolve a ticket on her own quickly without the need to have John resolve it, lightening the load on John. This also shows the importance of documentation as the ticket was able to be resolved and another agent wouldn't accidentally work a ticket that is already done. The documentation can also be later used to fix the problem in the future, ensuring smoother operations within the company.
