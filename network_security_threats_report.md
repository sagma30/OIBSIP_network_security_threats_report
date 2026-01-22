# OIBSIP_Network_Security_Threats_Report
### Oasis Infobyte Internship - Task 4 Completed ✅
This repository contains a research-based report on common network security threats, created as part of my Security Analyst Internship. 
The report focuses on understanding how major network attacks work, their real world impact, and how defenders can detect and mitigate them.

## 1. DoS / DDoS Attacks

### How It Works
Attackers overwhelm a target with excessive traffic, exhausting bandwidth or system resources. DDoS uses multiple compromised systems to amplify the attack.

### Impact

- Service outages and downtime
- Financial and reputational damage
- Disruption of critical online services

### Mitigation & Prevention

- Rate limiting and traffic filtering
- DDoS protection services and CDNs
- IDS/IPS and network monitoring

### Real-World Example
Large scale DDoS attacks on DNS providers have caused widespread outages for major web services by targeting availability.

## 2. Man-in-the-Middle (MITM) Attacks

### How It Works
Attackers intercept communication between two parties, allowing them to read or modify data without detection.

### Common Techniques

- ARP spoofing
- DNS poisoning
- Rogue Wi-Fi access points

### Impact

- Credential theft
- Data manipulation
- Loss of confidentiality and trust

### Mitigation & Prevention

- Enforcing HTTPS and TLS
- VPN usage on untrusted networks
- Network monitoring and certificate validation

### Real-World Example
Public Wi-Fi MITM attacks have been used to capture user credentials by intercepting unencrypted traffic.

## 3. Spoofing Attacks

### How It Works
Attackers impersonate trusted entities to gain unauthorized access or redirect traffic.

### Common Types

- IP spoofing
- ARP spoofing
- Email spoofing

### Impact

- Bypassing access controls
- Enabling MITM attacks
- Phishing leading to malware or ransomware

### Mitigation & Prevention

- Ingress and egress packet filtering
- Dynamic ARP Inspection (DAI)
- Email authentication (SPF, DKIM, DMARC)

### Real-World Example (2025)
The RaccoonO365 phishing campaign used advanced email spoofing to steal over 5,000 Microsoft 365 credentials before being taken down by Microsoft and Cloudflare.

## Conclusion

Network attacks such as DoS/DDoS, MITM, and spoofing remain some of the most common threats targeting modern networks. These attacks primarily impact availability, confidentiality, and trust, making them critical concerns for organizations of all sizes. From a defender and SOC analyst perspective, early detection, continuous monitoring, and layered security controls are essential to reduce risk. Understanding how these attacks operate helps security teams respond faster, minimize damage, and strengthen overall network resilience. Understanding how these attacks operate enables security teams to respond faster, reduce attack impact, and strengthen overall network resilience in real-world environments.
