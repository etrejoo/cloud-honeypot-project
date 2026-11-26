# Cloud-Based Honeypot Environment

## Overview
This project demonstrates the deployment of a cloud-based honeypot environment using AWS, Linux, Cowrie, and T-Pot.

## Technologies Used
- AWS EC2
- Ubuntu
- Cowrie
- T-Pot
- ELK Stack

## Skills Demonstrated
- Security Monitoring
- Log Analysis
- Threat Detection
- Cloud Security
- Linux Administration

## Project Objectives
- Capture unauthorized access attempts
- Analyze attacker behavior
- Monitor security events
- Improve visibility into network threats

## Screenshots
<img width="2953" height="1841" alt="Copy of Blank diagram (2)" src="https://github.com/user-attachments/assets/8c7748f2-7998-49de-98c7-6bb7de432349" />
Architecture of the cloud-based honeypot environment deployed in AWS.

<img width="2114" height="1532" alt="Screenshot 2026-11-04 195616" src="https://github.com/user-attachments/assets/1a6791a5-b384-4b6a-b2c0-1c3669000556" />
This dashboard provides visibility into attack activity targeting the honeypot environment.

<img width="2044" height="1032" alt="Screenshot 2026-11-25 222905" src="https://github.com/user-attachments/assets/e011d4f3-7861-455e-a3ed-83db1aa4799f" />
Cowrie SSH honeypot capturing command activity following successful interaction with the honeypot. Observed commands include system discovery techniques. This also shows multiple failed SSH login attempts captured by Cowrie. These events demonstrate automated credential guessing and unauthorized access attempts.

## Lessons Learned
- Configuring cloud security controls
- Monitoring and analyzing logs
- Understanding common attack patterns
