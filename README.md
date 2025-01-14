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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2> Intake </h2>
The ticket intake process involves creating or receiving a ticket through one of several channels:

Channels for Ticket Creation:

Email: When a user emails the designated support email address, osTicket automatically converts the email into a ticket.
Web Portal: Users can submit tickets directly through the help desk's customer portal.
API: Developers can integrate osTicket with external systems to create tickets programmatically.
Ticket Details:

User information (name, email, etc.).
Subject and description of the issue.
Attachments or relevant files.
Auto-Response:

osTicket sends an automatic acknowledgment email to the user, confirming ticket creation.
The auto-response includes the ticket ID for tracking.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2> Assignment and Communication </h2>
Once a ticket is created, it is assigned and initial communication begins.

Ticket Assignment:

Manual Assignment: Staff or admins can assign tickets to specific agents or teams based on the issue.
Automatic Assignment: Tickets can be routed to departments or agents based on:
Help topics.
Predefined ticket filters.
Ticket priorities.
Communication with the User:

Agents can respond to the ticket directly within osTicket.
All communications are logged in the ticket thread for easy tracking.
Email notifications are sent to users when agents respond or request additional information.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>  Working the Issue </h2>
Agents actively work to resolve the ticket.

Investigating the Issue:

Agents analyze the problem described in the ticket.
They may ask the user for additional details or clarification.
Collaboration:

Agents can add internal notes to the ticket, visible only to other agents.
Collaborate with other departments or escalate the ticket if required.
Tracking Time and Progress:

Agents can log time spent on the ticket using the time tracking feature.
Update the ticket status to reflect progress (e.g., "Open," "In Progress," "On Hold").
SLA Compliance:

Ensure the ticket is addressed within the defined Service Level Agreement (SLA) timeframe.
SLA alerts notify agents of approaching deadlines.

<h2> Resolution </h2>
The ticket is resolved, and the process is concluded.

Providing a Solution:

Agents provide the final resolution to the user.
Attach necessary documentation, screenshots, or guides if needed.
Closing the Ticket:

Once the user confirms satisfaction or the agent resolves the issue, the ticket status is updated to "Closed."
Auto-close rules can also mark tickets as resolved after a specified period of inactivity.
Feedback and Review:

Users can submit feedback on their experience.
Administrators can review ticket data for quality control or reporting.

<h2> Key osTicket Features Supporting the Lifecycle </h2>
Dashboard and Reports: Monitor ticket statuses, response times, and resolution metrics.
Help Topics and Forms: Streamline ticket creation with preconfigured topics.
Ticket Filters and Automations: Automate ticket routing and actions.
Knowledgebase: Provide users with self-help options to reduce ticket volume.

</p>
<br />
