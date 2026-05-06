# SYN Flood Attack Analysis

## Overview
This project analyzes a cybersecurity incident involving a TCP SYN flood attack targeting a company web server.

The investigation focuses on identifying the attack type, analyzing abnormal network traffic, assessing the impact on business operations, and documenting response actions.

## Objective
- Identify the type of network attack
- Analyze suspicious TCP SYN traffic
- Assess the impact on the web server
- Document incident response actions
- Recommend future mitigation strategies

## Attack Type
- TCP SYN Flood Attack
- Denial of Service (DoS)

## Key Findings
- Large number of TCP SYN requests from an unfamiliar IP address
- Web server became overwhelmed and unresponsive
- Users experienced connection timeout errors
- Firewall blocking was temporarily implemented

## Project Structure
- incident-report.md
- attack-analysis.md
- impact-assessment.md
- recommendations.md

## Outcome
The investigation determined that the server was experiencing a TCP SYN flood attack designed to overwhelm server resources and disrupt website availability.

## References

- [Cybersecurity Incident Report Template](docs/incident-report-template.pdf)
- [Wireshark TCP/HTTP Log](docs/wireshark-tcp-http-log.pdf)
