# Alert Ticket.md

Disclaimer:

💡 The steps in this playbook are not a definitive guide to responding to a phishing incident. 
Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.

### Update the ticket alert status

<img src="" width="500" /> 

<img src="" width="500" /> 

### Evaluate the alert
2-3 reasons on why you believe the phishing alert is or isn't legitimate.
- The alert severity is medium which is a good indication that a ticket might require escalation.
- There is a mismatch between the sender's email address (Def Communications <76tguyhh6tgftrt7tg.su>) and the sender's name (Clyde West), this is a good indication that the email might be a phishing email.
- The message body and subject line contain grammatical errors, which can be an indication of a phishing attempt. This is indicated by green in the image below.
- A malicious file has been attached to this email. This is indicated by pink in the image below.

<img src="" width="500" />

### Determine whether the alert should be escalated
It was already determined that the email contains an attachment that has been verified as malicious through its file hash in the previous activity.
Therefore, the alert should be escalated.

<img src="" width="500" />

### Update the ticket alert status

<img src="" width="500" />

Under the Ticket comments column of the alert ticket template, use the details you've found to explain the steps taken and why you chose to escalate or close the ticket. 
Include 2-3 reasons as to why you believe this alert should be escalated or closed.
