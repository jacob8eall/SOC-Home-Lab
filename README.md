# SOC Home Lab: Detecting Brute Force Attacks with Suricata & Wazuh

## Overview
This project simulates a Security Operations Center (SOC) workflow by setting up a home lab environment using Suricata IDS and Wazuh SIEM. The goal was to detect and analyze brute force attacks against an SSH service and document the incident response process.

## Tools & Technologies
- Suricata IDS
- Wazuh SIEM
- Ubuntu Linux
- Hydra (for brute force simulation)

## Key Steps
1. Deployed Suricata to monitor network traffic.
2. Configured Wazuh to collect and analyze alerts.
3. Launched a brute force attack using Hydra.
4. Verified detection in Suricata logs.
5. Created an alert in Wazuh and documented the incident.

## Results
- Successfully detected multiple failed SSH login attempts.
- Suricata generated alerts that were ingested by Wazuh.
- Documented incident workflow: Detection → Analysis → Response.

## Screenshots
![Suricata Alert](screenshots/alert_detected.png)  
![Wazuh Dashboard](screenshots/wazuh_dashboard.png)

## What I Learned
- Hands-on experience configuring IDS/IPS tools.
- How SOC analysts monitor and escalate incidents.
- Importance of centralized logging in real-world environments.
