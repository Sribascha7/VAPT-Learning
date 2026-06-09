# MAC and ARP

## Overview

A MAC address is a unique hardware identifier assigned to a network interface. ARP (Address Resolution Protocol) maps IP addresses to MAC addresses on local networks.

## Core Concepts

- MAC Address
- ARP Request
- ARP Reply
- ARP Cache
- ARP Spoofing

## How It Works

When a device wants to communicate locally, ARP is used to find the MAC address associated with the destination IP address.

## Practical Example

```text
Who has 192.168.1.1?

192.168.1.1 is at 00:11:22:33:44:55
```

## Common Commands

```bash
arp -a
ip neigh
```

## VAPT Relevance

- Local Network Enumeration
- ARP Poisoning Detection
- Man-in-the-Middle Attack Analysis

## Summary

Understanding MAC addresses and ARP is essential for analyzing local network communication and Layer 2 attacks.
