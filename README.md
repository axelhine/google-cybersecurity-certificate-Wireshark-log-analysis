# google-cybersecurity-certificate-Wireshark-log-analysis

A network security incident analysis completed as part of the **Google Cybersecurity Certificate**. This project uses Wireshark packet capture data to identify and explain a SYN flood Denial of Service (DoS) attack against a company web server.

## About This Project

A company's website became unreachable, triggering a connection timeout for all users. Using Wireshark to capture live network traffic, I identified an abnormal volume of TCP SYN requests originating from a single IP address, diagnosed the attack type, and explained how it disrupted normal server operations.

## Files in This Repository

- [Cybersecurity-Wireshark-log-inscident-report.pdf](Wireshark log inscident report.pdf) — full written incident report, including the scenario, technical analysis, recommendations, and raw Wireshark log data

## What This Project Covers

- **Attack Identification** — diagnosing a SYN flood / Denial of Service (DoS) attack from traffic patterns in a Wireshark capture
- **TCP Three-Way Handshake Analysis** — explaining how SYN, SYN-ACK, and ACK packets work, and how an attacker exploits incomplete handshakes to exhaust server resources
- **Business Impact Assessment** — connecting a technical outage to real business consequences (lost sales, employee disruption, reputational damage)
- **Mitigation Recommendations** — proposing SYN cookies and firewall rate limiting as practical countermeasures

## Skills Demonstrated

- Packet capture analysis using Wireshark
- Understanding of TCP/IP protocol behavior
- DoS/SYN flood attack recognition
- Incident reporting and technical communication
- Security control recommendations

---
*Completed as part of the Google Cybersecurity Professional Certificate.*
