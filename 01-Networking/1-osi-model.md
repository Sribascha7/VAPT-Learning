# OSI Model

## What is it?

The OSI (Open Systems Interconnection) Model is a conceptual framework that explains how data travels across a network through seven layers.

## Key Concepts

### Layer 1 - Physical Layer

* Cables
* Signals
* Hubs
* Data Transmission

### Layer 2 - Data Link Layer

* MAC Addresses
* Switches
* Frames
* Error Detection

### Layer 3 - Network Layer

* IP Addresses
* Routers
* Packet Routing

### Layer 4 - Transport Layer

* TCP
* UDP
* Segmentation
* Reliable Communication

### Layer 5 - Session Layer

* Session Establishment
* Session Management
* Session Termination

### Layer 6 - Presentation Layer

* Encryption
* Compression
* Data Formatting

### Layer 7 - Application Layer

* HTTP
* HTTPS
* DNS
* FTP
* SMTP

## How It Works

Data moves from the Application Layer down to the Physical Layer on the sender's side and travels across the network. The receiving device processes the data from the Physical Layer back up to the Application Layer.

## Practical Example

When browsing a website:

1. HTTP operates at the Application Layer.
2. TLS secures the data at the Presentation Layer.
3. TCP establishes a reliable connection at the Transport Layer.
4. IP determines the destination at the Network Layer.
5. Ethernet frames are created at the Data Link Layer.
6. Data is transmitted through cables or Wi-Fi at the Physical Layer.

## Common Commands

ping google.com

traceroute google.com

tcpdump -i eth0

wireshark

## VAPT Relevance

* Network Troubleshooting
* Protocol Analysis
* Attack Surface Mapping
* Vulnerability Classification
* Packet Analysis
* Security Monitoring

### Common Layer-Based Attacks

* Layer 2: ARP Spoofing
* Layer 3: IP Spoofing
* Layer 4: TCP SYN Flood
* Layer 7: SQL Injection
* Layer 7: Cross-Site Scripting (XSS)

## Tools

* Wireshark
* TCPDump
* Nmap
* Burp Suite
* Netcat

## Summary

The OSI Model helps security professionals understand network communication, identify where attacks occur, troubleshoot network issues, and perform effective vulnerability assessments.
