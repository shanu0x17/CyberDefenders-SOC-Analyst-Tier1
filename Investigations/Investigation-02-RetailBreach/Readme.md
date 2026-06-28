# RetailBreach Lab

> **Platform:** CyberDefenders  
> **Category:** Network Forensics  
> **Difficulty:** Easy  
> **Tools:** Wireshark, NetworkMiner, Brim  

---

## Overview

This investigation focused on analyzing network traffic from a compromised retail web application using a provided PCAP file. The objective was to identify the attacker's techniques, investigate the exploitation of the web application, reconstruct the attack timeline, and understand how the compromise led to unauthorized access.

---

## What I Did

During this investigation, I:

- Analyzed the provided PCAP file using Wireshark.
- Identified the attacker's IP address through network traffic analysis.
- Investigated directory brute-forcing activity used to discover hidden web paths.
- Examined malicious HTTP requests targeting the vulnerable web application.
- Analyzed the Cross-Site Scripting (XSS) payload used during the attack.
- Investigated the theft and use of a compromised session token.
- Identified the vulnerable script exploited by the attacker.
- Examined the payload used to access sensitive files on the target system.
- Correlated the observed attacker activity with the MITRE ATT&CK framework.

---

## Skills Practiced

- PCAP Analysis
- HTTP Traffic Analysis
- Web Application Security Investigation
- XSS Analysis
- Session Hijacking Investigation
- IOC Identification
- MITRE ATT&CK Mapping

---

## Key Learnings

- Learned how XSS attacks can be identified through packet analysis.
- Understood how session tokens can be stolen and abused for unauthorized access.
- Investigated directory brute-force techniques used during reconnaissance.
- Improved the ability to reconstruct attacker activity using captured network traffic.
- Gained practical experience correlating web application attacks with MITRE ATT&CK tactics.

---

## Reflection

This investigation strengthened my understanding of web application attack analysis and demonstrated how network forensics can be used to reconstruct complex attack scenarios involving XSS exploitation, session hijacking, and unauthorized access.
