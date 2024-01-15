<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
End Users log in to http://localhost/osTicket/ and click "Open a New Ticket." add your email/full name and number then select a Help Topic. The panel with expand. Input a summary of the issue under "Please Describe Your Issue" and give a detail describtion for opening the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents will then log in on the other end http://localhost/osTicket/scp/login.php Go to Admin Panel then click "Ticket" where you'll be able to see the problems as an admin. Click on the ones that are arranged to be finished in the shortest time period (SEV-A is first priority) Adjust prioties to the appropriate problems if necessary. To do so click "Priority" (normal/emergency/low/high) // click "Unassigned" (assign to appropriate agent). click "'Default SLA" (SEV-A/SEV-B/SEV-C)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents can further respond to end users using the text bar under "Post Reply." Agents can select a canned responses, adjust the recipient (person who will recieve the message) or send to all. If the problem hasn't been resolved then keep the ticket on "open" statis while relaying messages to end users. If the issue is cleared change the statis of the ticket and it will be removed from the "open" section and sent to the "closed" section.
</p>
<br />
