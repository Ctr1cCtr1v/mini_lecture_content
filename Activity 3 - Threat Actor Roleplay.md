# "A Day in the Life of a Cyber Attack"
## Scenario Overview:
You are simulating an ongoing attack on XYZ Corporation, a mid-sized company that develops specialized software for financial institutions. The company stores sensitive financial data, proprietary algorithms, and customer information on its network. Unfortunately, their cybersecurity hygiene has deteriorated, leaving them vulnerable to exploitation.

The students will split into two groups—**Threat Actors** and **Defenders**. Each side will analyze the company's weaknesses and plan their strategies.

## Company’s Current Cybersecurity Posture:
* Weak Password Policy: Many employees use simple passwords like "Password123" or "Welcome2023".
* Unpatched Systems: The IT department is behind on applying critical patches, leaving systems vulnerable to known exploits.
* No Multi-Factor Authentication (MFA): Only usernames and passwords are required to access critical systems.
* Insufficient Network Segmentation: All internal systems are on a flat network, meaning if one system is compromised, attackers have access to everything.
* Inconsistent Employee Security Training: Most employees haven’t received security awareness training in over a year, and phishing simulations have not been conducted.
* Old Firewall Configuration: The firewall is improperly configured, with several unused but open ports left exposed to the internet.



## Threat Actor Role:
As Threat Actors, your goal is to exploit XYZ Corporation’s weaknesses to breach the network, steal sensitive data, and maintain persistence.

### Steps for Threat Actors:
* Reconnaissance: How will you find any information that might give you a foothold?
* Initial Access: How will you attempt to gain access?
* Lateral Movement: Once inside the network, how will you move laterally to gain deeper access? 
Hint: What types of critical data or systems would you prioritize targeting (e.g., financial data, proprietary software code)?
* Persistence: How will you ensure that you maintain access even after the defenders realize the system has been compromised?
* Exfiltration: What’s your exit strategy for getting the stolen data out without triggering alarms?

## Defender Role:
As Defenders, your goal is to secure the network by addressing XYZ Corporation’s vulnerabilities, identify the attacker’s actions, and respond quickly to prevent data loss.

### Steps for Defenders:
* Strengthen Access Controls: How will you immediately tighten the company’s access controls to prevent attackers from getting in?
* Patch and Protect: How will you prioritize patching the company's outdated systems?
* Segment the Network: What steps will you take to improve network segmentation?
* Detect and Respond to Intrusion: If you suspect an attacker has breached your network, how will you detect their activities?
* Incident Response: If an attacker is already inside the network, how will you contain and eradicate them?
