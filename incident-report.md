# Cybersecurity Incident Report

## Incident Summary

A web server outage affected the travel agency’s website, preventing employees and customers from accessing vacation package information online. Users experienced connection timeout errors when attempting to load the website.

Network traffic analysis revealed a large volume of TCP SYN requests originating from an unfamiliar IP address. The abnormal traffic overwhelmed the web server and reduced its ability to respond to legitimate user requests.

The attack was identified as a TCP SYN flood attack, a form of Denial of Service (DoS) attack.

---

## Investigation Details

### How the Incident Was Identified
The security team received an automated monitoring alert indicating abnormal web server activity and service interruptions.

### Actions Taken
- The analyst attempted to access the website and confirmed the timeout issue
- A packet sniffer was used to analyze network traffic
- Suspicious TCP SYN traffic was identified
- The affected server was temporarily taken offline
- Firewall rules were updated to block the suspicious IP address

### Key Findings
- Excessive TCP SYN requests targeted the web server
- Requests originated from an unfamiliar IP address
- The server became overloaded and unable to respond normally
- Legitimate users experienced website connection failures

### Current Status
The issue was escalated to management and security engineers for further mitigation and prevention planning.
