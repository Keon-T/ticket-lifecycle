<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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
<img src="https://i.imgur.com/xEQNruj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating a ticket as an end user opening new ticket as karen with help topic reporting business critical outage/report problem</p>
login osticket virtual machine on and running copy IP address to use for remote desktop login open two tabs for OS and login as admin user previously created and go to admin panel - agents - departments - maintenance department save all changes and open new ticket as end user karen business critical report problem

 - As an end-user, create the following ticket
entire mobile/online banking system is down

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-A (1 hour, 24/7)
Online Banking Department

<br />

<p>
<img src="https://i.imgur.com/5mqoTzU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
login in with different credentials to observe as help desk agent john to select priority/department and setting service level agreement (sla) assigning to completion
Work the previous ticket to completion as john , As an end-user, create the following ticket
CFO’s laptop will no longer turn on as a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To
Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support
then completing ticket as john

</p>
<br />

<p>
<img src="https://i.imgur.com/nZhvtsL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Another new a ticket as an end user opening new ticket as karen with help topic reporting business critical outage/report problem</p>
Pretending that we are the cfo making a ticket report a problem personal computer issues setting priority to emergency classifying SLA sev B attempt to call,contact with RESPONSE to problem and set status to resolved 

Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
Switch to admin panel and assign yourself View-access to Sys Admins
Switch to agent panel and observe the escalated ticket
Observe that you can no longer make changes to it

<br />
