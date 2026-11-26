# Cloud Honeypot Project

## Overview
This project demonstrates the deployment of a cloud-based honeypot environment using AWS, Ubuntu, Cowrie, and T-Pot. The objective was to capture, monitor, and analyze unauthorized access attempts and attacker behavior in a controlled environment.

## Technologies Used
- AWS EC2
- Ubuntu
- Cowrie
- T-Pot
- ELK Stack
- SSH
- Security Monitoring

## Skills Demonstrated
- Security Monitoring
- Log Analysis
- Threat Detection
- Network Security
- Linux Administration
- Vulnerability Assessment

## Architecture
### AWS Honeypot Architecture

Architecture of the cloud-based honeypot environment deployed in AWS. The environment uses T-Pot and multiple honeypot services to capture, collect, and analyze attack activity for security monitoring and research.

<img width="2953" height="1841" alt="Copy of Blank diagram (2)" src="https://github.com/user-attachments/assets/8c7748f2-7998-49de-98c7-6bb7de432349" />

## Screenshots

### Security Monitoring Dashboard
Elastic dashboard displaying attack activity captured across multiple honeypot services. The dashboard provides visibility into attack volume, source locations, targeted services, and overall threat trends observed within the environment.

<img width="2114" height="1532" alt="Screenshot 2026-11-04 195616" src="https://github.com/user-attachments/assets/1a6791a5-b384-4b6a-b2c0-1c3669000556" />

### Attacker Reconnaissance Activity

Cowrie SSH honeypot capturing command activity following successful interaction with the honeypot. Observed commands include system discovery techniques. This also shows multiple failed SSH login attempts captured by Cowrie. These events demonstrate automated credential guessing and unauthorized access attempts.

<img width="2044" height="1032" alt="Screenshot 2026-11-25 222905" src="https://github.com/user-attachments/assets/e011d4f3-7861-455e-a3ed-83db1aa4799f" />

## Key Findings

- The honeypot successfully captured repeated SSH authentication attempts.
- Attackers commonly performed system reconnaissance commands after gaining access.
- Elastic dashboards provided centralized visibility into attack patterns and activity.
- Cloud-based honeypots can generate useful security telemetry for monitoring and analysis.

## Lessons Learned

- Deploying security tools in AWS environments.
- Configuring Linux-based monitoring platforms.
- Collecting and analyzing security logs.
- Understanding attacker reconnaissance techniques.
- Using Elastic Stack for security analytics.
