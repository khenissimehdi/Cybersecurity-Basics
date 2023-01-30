# Intrusion detection & prevention

## Importance of Intrusion Detection Systems (IDS):
- Error in system configuration
- Detection of hackers/crackers
- Detection and prevention of intrusion

## Types of IDS:
- System IDS: verifies data integrity and searches for malware left by attacker. Example: AIDE
- Network IDS: listens to the network for suspicious traffic signatures. Example: Snort
- Intrusion Prevention System (IPS): IDS that can be configured to remove the attack when detected.

## Honeypots:
- Definition: A machine that simulates common security weaknesses and is monitored for detection of scans and intrusions. Example: Honeyd (Virtual HoneyPot)

## Authentication servers:
- Centralize the process of identifying people or machines connecting to network resources.

Three principles used to verify identity:
- Something you are (e.g. fingerprint)
- Something you have (e.g. smart card)
- Something you know (e.g. password)

Examples: Tacacs+, RADIUS, Diameter

## 802.1x standard:
- Used for access control
- Exchange of authentication takes place using EAP (Extensible Authentication Protocol) between the requester and the authentication server
- AAA (Authentication, Authorization, Accounting) protocol is used by the authentication servers.

Types of EAP: LEAP (Cisco specific), EAP-MD5, EAP-TLS, EAP-TTLS, PEAP.
