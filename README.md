# Snort-IDS-Project
## Custom Snort IDS Rules for Network Traffic Monitoring and Data Protection

## Project Objective
Develop and implement custom Snort intrusion detection rules to monitor and secure a private network environment by:

- Detecting inbound and outbound HTTP traffic to monitor web activity.
- Identifying unauthorized FTP login attempts with specific usernames and passwords.
- Monitoring and alerting on the unauthorized exfiltration of sensitive files over HTTP.
- Capturing file access attempts to sensitive and non-sensitive resources.

This project showcases practical skills in network security monitoring, threat detection, and rule-based intrusion prevention.

---

## Tools Used

| Tool        | Purpose                                               |
|-------------|------------------------------------------------------|
| Snort IDS   | Writing and deploying custom detection rules; capturing and analyzing alerts for HTTP and FTP traffic, and file access |
| Kali Linux  | Running Snort and simulating network traffic in a controlled environment |
| Windows VM  | Generating network traffic on a private host-only network for monitoring and testing purposes |
| PuTTY/Terminal | Executing Snort and reviewing live alerts and logs |

---

## Implementation Overview

1. Created custom Snort rules to monitor both inbound and outbound HTTP traffic across the private network, capturing web activity.
2. Developed detection rules targeting FTP login attempts using the username **"root"** combined with specific suspicious passwords.
3. Designed a rule to detect attempts to exfiltrate the confidential file `FX-ME-191-Secret-Plans.txt` via HTTP, enhancing data loss prevention.
4. Configured alerts to monitor access attempts on both sensitive files (`FX-ME-192-Secret-Plans.txt`) and standard files (`customer.csv`), verifying rule effectiveness.

---

## Skills Gained
- Mastery of Snort rule syntax, including content matching and directional operators.
- Hands-on experience detecting protocol-specific traffic and user behavior anomalies.
- Real-time analysis and validation of network intrusion alerts.
- Implementing targeted data exfiltration monitoring for enhanced security posture.
- Working with virtualized private network setups for secure testing environments.

---

## Visual Results

### HTTP Traffic Monitoring  
![HTTP Traffic Alerts](https://i.imgur.com/ER0JPoD.png)  
*Alerts generated from monitoring inbound and outbound HTTP traffic, providing insight into web activity across the private network.*

### FTP Login Attempts Detection  
![FTP Login Alerts](https://i.imgur.com/ZirDezg.png)  
*Detection of FTP login attempts with username "root" and suspicious passwords, highlighting potential unauthorized access.*

### Sensitive File Exfiltration Alert  
![HTTP File Exfiltration Alert](https://i.imgur.com/L082GYq.png)  
*Alert triggered by unauthorized HTTP transfer of a confidential file, supporting data leakage prevention efforts.*

### Sensitive File Access  
![Secret File Access](https://i.imgur.com/v0dc7Bj.png)  
*Notification of access attempts to protected sensitive files within the network.*

### Non-Sensitive File Access Monitoring  
![Customer CSV Access](https://i.imgur.com/AeU68e4.png)  
*Alerts related to access of standard files, providing baseline network activity insights.*

### Sensitive File Access Confirmation  
![Secret Plans Access](https://i.imgur.com/GymHW3n.png)  
*Verification alerts when sensitive files are accessed, confirming rule accuracy and network monitoring effectiveness.*

---

## Summary
This project demonstrates advanced intrusion detection capabilities through customized Snort rules tailored for a private network. By monitoring HTTP and FTP protocols, as well as sensitive file activity, it effectively identifies unauthorized access attempts and data exfiltration risks.

The approach integrates precise packet inspection with directional traffic analysis, enabling proactive threat detection and strengthening network defense strategies. Running the project in a virtualized host-only environment provided a secure platform to simulate and validate real-world network security scenarios.

---

*Karishma Tallreja*  

