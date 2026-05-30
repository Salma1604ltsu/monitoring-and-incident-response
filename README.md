# Monitoring and Incident Response

## Objective
To detect and respond to security incidents using blue team tools and processes, including log analysis, threat detection, and incident response documentation.

## Tools Used
- Splunk
- Kali Linux
- Nmap
- Wireshark

## Environment Setup
- Installed and configured Splunk Free Edition
- Configured log collection and indexing
- Connected Splunk to a test VM generating system and network logs

## Threat Detection Activities
### Port Scanning Detection
- Simulated reconnaissance attacks using Nmap
- Monitored network activity through Splunk dashboards
- Created alerts for suspicious scanning behavior

### Brute Force Detection
- Simulated SSH brute-force attacks using Hydra
- Created custom Splunk queries to detect failed login attempts
- Generated security alerts based on login anomalies

## Incident Response Workflow

### Incident
Port Scanning Detected

### Classification
- Type: Reconnaissance Attack
- Severity: Medium

### Containment
- Blocked suspicious IP addresses
- Enabled rate limiting

### Eradication
- Verified no compromise occurred
- Hardened exposed services
- Disabled unused ports

### Recovery
- Restored monitoring operations
- Increased alert sensitivity

## Improvement Recommendations
- Implement SOAR automation
- Update detection rules regularly
- Enable centralized logging

## Screenshots
Store all screenshots in the screenshots folder.

## Disclaimer
This project was conducted in a controlled lab environment for educational and cybersecurity learning purposes only.
