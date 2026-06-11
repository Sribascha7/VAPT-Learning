# TCP and UDP

## What is it?
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are Transport Layer protocols responsible for data transmission between devices.

## Key Concepts
### TCP
- Connection-oriented
- Reliable communication
- Three-Way Handshake
- Error checking and retransmission

### UDP
- Connectionless
- Faster communication
- No delivery guarantee
- Low overhead

## Example
- TCP: Web browsing, Email, SSH
- UDP: DNS, VoIP, Video Streaming

## VAPT Relevance
- Port scanning
- Service enumeration
- Network reconnaissance
- Attack surface identification

## Tools
- Nmap
- Wireshark
- Netcat

## Summary
TCP provides reliable communication while UDP provides faster communication with lower overhead.

---

# Common Ports

## What is it?
Ports identify specific services running on a system.

## Key Concepts
- Port Numbers
- Open Ports
- Closed Ports
- Filtered Ports

## Common Ports
- 21 FTP
- 22 SSH
- 23 Telnet
- 25 SMTP
- 53 DNS
- 80 HTTP
- 110 POP3
- 143 IMAP
- 443 HTTPS
- 3306 MySQL

## Example
An Nmap scan can identify open ports and running services.

## VAPT Relevance
- Service enumeration
- Attack surface mapping
- Vulnerability identification

## Tools
- Nmap
- Netcat
- Masscan

## Summary
Understanding common ports helps identify exposed services and potential attack vectors.
