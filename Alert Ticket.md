# Alert Ticket

Disclaimer:

💡 The steps in this playbook are not a definitive guide to responding to a phishing incident. 
Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.

### Update the ticket alert status

<img src="https://github.com/melaniedaniel7/Use-a-playbook-to-respond-to-a-phishing-incident/blob/4a5bf85c00fa5d63721c6f2b0d6e1076ad61be39/Screenshot%202024-11-20%20at%2020.47.01.png" width="500" /> 

<img src="https://github.com/melaniedaniel7/Use-a-playbook-to-respond-to-a-phishing-incident/blob/be9d92d1cbc1f15efbcfd2da2f1b9cb00d23fc90/Screenshot%202024-11-21%20at%2008.19.27.png" width="500" /> 

### Evaluate the alert
2-3 reasons on why you believe the phishing alert is or isn't legitimate.
- The alert severity is medium which is a good indication that a ticket might require escalation.
- There is a mismatch between the sender's email address (Def Communications <76tguyhh6tgftrt7tg.su>) and the sender's name (Clyde West), this is a good indication that the email might be a phishing email.
- The message body and subject line contain grammatical errors, which can be an indication of a phishing attempt. This is indicated by green in the image below.
- A malicious file has been attached to this email. This is indicated by pink in the image below.

<img src="https://github.com/melaniedaniel7/Use-a-playbook-to-respond-to-a-phishing-incident/blob/1cfcede16becca79fbeae29fba41e2dba9843ad5/Screenshot%202024-11-20%20at%2020.49.53.png" width="500" />

### Determine whether the alert should be escalated
It was already determined that the email contains an attachment that has been verified as malicious through its file hash in the previous activity.

Known malicious file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Therefore, the alert should be escalated.

<img src="https://github.com/melaniedaniel7/Use-a-playbook-to-respond-to-a-phishing-incident/blob/53f8f002b627c45e4b40e90578d9525b4bf09c64/Screenshot%202024-11-20%20at%2020.13.09.png" width="600" />

### Update the ticket alert status

<img src="https://github.com/melaniedaniel7/Use-a-playbook-to-respond-to-a-phishing-incident/blob/ea5d97218da4193d51dbeea324697717e5dddf40/Screenshot%202024-11-21%20at%2008.26.52.png" width="500" />

Include 2-3 reasons as to why you believe this alert should be escalated or closed. The ticket should be escalated because:
- The alert severity is medium which is a good indication that a ticket might require escalation.
- The email contains a password-protected attachment.
- The attachment was previously confirmed as malicious.
