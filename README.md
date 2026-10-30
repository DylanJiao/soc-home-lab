# SOC Home Lab
A hands-on SOC home-lab for learning networking and cybersecurity concepts and practicing technical skills.

## Learning Objectives
With this project, I plan to practice and improve my understanding of:
- Network communication and reconnaissance
- Windows event logging
- Endpoint telemetry
- SIEM log collection and analysis
- Security monitoring and detection
- Incident investigation
- Basic detection engineering
- MITRE ATT&CK mapping

## Planned Architecture
Pre-Checkpoint 5:
- Kali Linux VM: Used to generate controlled security activity
- Windows VM: Monitored endpoint
- Isolated virtual network: Allows the systems to communicate safely
![SOC Home Lab Network Architecture](screenshots/02-lab-network-diagram.png)
Post-Checkpoint 5:
- Ubuntu Server VM: SIEM using Splunk Enterprise
![SOC Home Lab Network Architecture Update](screenshots/05-updated-lab-network-diagram.png)

*Additional network and security tools will be added as the lab progresses.

## Project Status With Checkpoint Notes
- [x] Checkpoint 1 - Initial repository setup on GitHub.
- [x] [Checkpoint 2 - Virtual environment setup and basic network connectivity testing](notes/02-virtual-environment.md)
- [x] [Checkpoint 3 - Windows event log investigation](notes/03-windows-event-log-investigation.md)
- [x] [Checkpoint 4 - Sysmon installation and event analysis](notes/04-sysmon-endpoint-telemetry.md)
- [x] [Checkpoint 5 - Splunk Enterprise integration](notes/05-splunk-enterprise-integration.md)

