# Hi, I'm Mario Segrt

Cybersecurity analyst focused on security and detection engineering for cloud and identity.

## About Me

I design, deploy, and test lab environments across endpoints, networks, cloud, and identity to emulate real world attack paths, then use the telemetry to build detections, hardening strategies, and security controls for both cloud and on‑prem environments.

## Certifications

- PNPT - Practical Network Penetration Tester
- BTL1 - Blue Team Level 1
- CompTIA Security+
- Microsoft AZ-500 - Azure Security Engineer (In Progress)

## Current Focus

- Detection Engineering - SIEM rules, KQL, Sigma, and log-based detections
- Identity and cloud security - working through PwnedLabs and other offensive labs to attack Entra/Azure identities and turn those attacks into detections
- Attack–defend labs across endpoint, network, and cloud environments
- Azure security with an emphasis on identity, access, and monitoring
- SOC operations from alert triage through investigation and threat hunting

## Projects

Enterprise Homelab

Built a small enterprise environment from scratch and took it from clean install to full domain breach.

- Spun up VMs for a domain controller, Windows 11 and Ubuntu workstations, an Ubuntu server running MailHog, a Wazuh security server (SIEM), and a Kali attacker machine.
- Set up AD, DNS, and joined the relevant machines to the domain with real user accounts.
- Used MailHog to send and catch phishing emails and test credential harvesting safely.
- Wired everything into a SIEM so logs from hosts and the network all land in one place.
- Ran a full attack path (phishing -> foothold -> lateral movement -> privilege escalation) and walked through it using the collected telemetry.

Key achievement: Baseline enterprise style lab that I’ll keep expanding with new tools, attacks, detections, and hardening as I level up.
