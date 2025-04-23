# Alert Ticket

## Objective
I was tasked with analyzing the given information and write up an alert ticket to represent my thoughts on the email. It is a phishing email including a file attachment with a password needed, for which it would then download the malicious file onto the machine using it. I need to find more information on the alert and what steps should be taken next. Information on the email and attachment are shown below.

Known malicious file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Email:
From: Def Communications <76tguyhh6tgftrt7tg.su>  <114.114.114.114>
Sent: Wednesday, July 20, 2022 09:30:14 AM
To: <hr@inergy.com> <176.157.125.93>
Subject: Re: Infrastructure Egnieer role

Dear HR at Ingergy,

I am writing for to express my interest in the engineer role posted from the website.

There is attached my resume and cover letter. For privacy, the file is password protected. Use the password paradise10789 to open. 

Thank you,

Clyde West
Attachment: filename="bfsvc.exe"


### Skills Learned
[Bullet Points - Remove this afterwards]

- Proficiency in analyzing a file hash and if it malicious
- Ability to effectively write up an alert ticket
- An understanding of what actions should be taken next after alert


### Tools Used
[Bullet Points - Remove this afterwards]

- VirusTotal
- MetaDefender


### Work Completed

**Ticket ID:** A-2703<br>
**Alert Message:** SERVER-MAIL Phishing attempt possible download of malware<br>
**Severity:** Medium<br>
**Details:** The user may have opened a malicious email and opened attachments or clicked links.<br>
**Ticket status:** Escalated<br>
<br>
**Ticket Comments:**
The alert came from an employee that downloaded and opened a malicious file from a phishing email. Email stuck out first since the sender’s email address, “76tguyhh6tgftrt7tg.su”, did not match the name used at the end of the body, “Clyde West”. The email also contained multiple grammatical errors like “Egnieer” in the subject line, and  “I am writing for to express” in the body section. The sender sent a file attachment, “bfsvc.exe”, with a password on it, which was downloaded and caused the machine used to be affected. After looking up the file hash, it was confirmed that the file was malicious. Furthermore, the severity of the alert was then reported as medium and ticket status was then raised to “escalated”. This required the ticket to move to a level-two SOC analyst to further investigate. 


