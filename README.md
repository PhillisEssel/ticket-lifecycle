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
<h3>Phase One</h3>
  
![osTicket-Ticketing Lifestyle Phase 1 - Imgur](https://github.com/PhillisEssel/ticket-lifecycle/assets/156061642/ebde9fe6-f440-4a2a-9449-c9ed57f8a3e7)

 
<p><a href="https://imgur.com/a/tCQfATt">More</a></p>

</p>
<p>
End Users log in to http://localhost/osTicket/ and click "Open a New Ticket." add your email/full name and number then select a Help Topic. The panel with expand. Input a summary of the issue under "Please Describe Your Issue" and give a detail describtion for opening the ticket.
</p>
<br />

<p>
<h3>Phase Two</h3>

![osTicket-Ticketing Lifestyle Phase 2 - Imgur](https://github.com/PhillisEssel/ticket-lifecycle/assets/156061642/ce23ab50-3283-47fb-9d8a-afc9bbef676f)

<p><a href="https://imgur.com/a/dj7lAaU">More</a></p>

</p>
<p>
Agents will then log in on the other end http://localhost/osTicket/scp/login.php Go to Admin Panel then click "Ticket" where you'll be able to see the problems as an admin. Click on the ones that are arranged to be finished in the shortest time period (SEV-A is first priority) Adjust prioties to the appropriate problems if necessary. To do so click "Priority" (normal/emergency/low/high) // click "Unassigned" (assign to appropriate agent). click "'Default SLA" (SEV-A/SEV-B/SEV-C)
</p>
<br />

<p>
<h3>Phase Three</h3>

![osTicket-Ticketing Lifestyle Phase 3 - Imgur](https://github.com/PhillisEssel/ticket-lifecycle/assets/156061642/6353fbb0-3c51-44a4-b942-64a7e6098d57)
<p><a href="https://imgur.com/a/1KnwHxw">More</a></p>

</p>
<p>
Agents can further respond to end users using the text bar under "Post Reply." Agents can select a canned responses, adjust the recipient (person who will recieve the message) or send to all. If the problem hasn't been resolved then keep the ticket on "open" statis while relaying messages to end users. If the issue is cleared change the statis of the ticket and it will be removed from the "open" section and sent to the "closed" section.
</p>
<br />
