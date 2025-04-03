# Passive Transparency – Systematic Logging

This project automates the capture and publication of the following data:

- Incoming network traffic  
- Executed commands (bash history and netstat)  
- System modifications and recent files  
- Exportable daily report  
- Precise traces of intrusions with geolocation  
- Visual mapping of detected attacks  
- Identification of potentially masked VPN IPs  

## Objective

Provide a minimalistic and technical foundation to publicly document a machine's activity, asserting a defense strategy based on full visibility.

**Goal:**

- Archive activity generated
- Reduce the appeal of malicious actions through constant exposure  

## Outcome

The `logs` folder contains subfolders corresponding to each day.  
- The `detected_attempts.log` file outlines the results of the analysis  
- The `summary_n-1` file allows focusing only on confirmed attacks. For each attack, it includes:  
    - The date of the attack  
    - The IP address of the attacker  
    - The country of origin  
    - The city of origin  
    - Approximate GPS coordinates of the source  


