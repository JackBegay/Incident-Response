# Incident Response Planning and Execution

## Objective
[Brief Objective - Remove this afterwards]
https://github.com/JackBegay/Detection-lab/tree/main
The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

**Ticket ID:** A-2703
**Alert Message:** SERVER-MAIL Phishing attempt possible download of malware
**Severity:** Medium
**Details:** The user may have opened a malicious email and opened attachments or clicked links.
**Ticket status:** Escalated
<br>
**Ticket Comments: **
The alert came from an employee that downloaded and opened a malicious file from a phishing email. Email stuck out first since the sender’s email address, “76tguyhh6tgftrt7tg.su”, did not match the name used at the end of the body, “Clyde West”. The email also contained multiple grammatical errors like “Egnieer” in the subject line, and  “I am writing for to express” in the body section. The sender sent a file attachment, “bfsvc.exe”, with a password on it, which was downloaded and caused the machine used to be affected. After looking up the file hash, it was confirmed that the file was malicious. Furthermore, the severity of the alert was then reported as medium and ticket status was then raised to “escalated”. This required the ticket to move to a level-two SOC analyst to further investigate. 


