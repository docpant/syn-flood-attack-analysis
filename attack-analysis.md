# Attack Analysis

## Type of Attack

The incident involved a TCP SYN flood attack, which is a type of Denial of Service (DoS) attack.

## Attack Characteristics

A SYN flood attack occurs when an attacker sends a large number of TCP SYN requests to a server without completing the TCP connection process. This causes the server to allocate resources for incomplete connections until it becomes overwhelmed.

## Evidence Observed

The packet analysis identified:
- High volumes of TCP SYN requests
- Repeated traffic from an unfamiliar IP address
- Connection timeout errors
- Reduced server responsiveness

## Protocol Involved

- TCP protocol
- SYN packets used during TCP connection establishment

## Impact on Network Operations

The excessive SYN requests consumed server resources and prevented legitimate users from successfully connecting to the website.
