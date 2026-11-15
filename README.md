# Ethernet Communication Investigation and Traffic Analysis using Linux

## Overview

This project focuses on investigating Ethernet communication and analysing network protocols using Ubuntu Linux and Wireshark.

The practical investigation covers ARP, ICMP, TCP and UDP protocols, along with DNS and NTP traffic. Wireshark is used to capture and inspect packets to understand network communication and the TCP/IP protocol stack.

## Objectives

- Understand Ethernet architecture and frame structure.
- Study MAC and IPv4 addressing.
- Investigate TCP and UDP protocols.
- Analyse ARP request and reply mechanisms.
- Understand ICMP Echo Request and Echo Reply.
- Capture and analyse network traffic using Wireshark.
- Perform network diagnostics using Linux commands.

## Tools and Technologies

- Ubuntu Linux
- Wireshark
- VirtualBox
- Linux Networking Utilities
- TCP/IP Protocol Suite

## Practical Activities

### 1. ARP Analysis

- Captured ARP request and reply packets.
- Observed MAC address resolution.
- Identified the IP address and corresponding MAC address.

### 2. ICMP Analysis

- Generated ICMP traffic using ping.
- Analysed Echo Request and Echo Reply packets.
- Observed communication between the local system and 8.8.8.8.

### 3. TCP Analysis

- Captured TCP traffic using Wireshark.
- Observed SYN and SYN-ACK packets.
- Analysed TCP acknowledgements and TLS application-data traffic.

### 4. UDP Analysis

- Captured UDP packets.
- Analysed DNS queries and responses.
- Observed NTP Version 4 communication.
- Investigated a malformed DNS packet reported by Wireshark.

## Linux Networking Commands

```bash
ip addr
ip route
arp -a
ping 8.8.8.8
ss -tuln
netstat -tuln
hostname -I
```

## Wireshark Display Filters

| Protocol | Display Filter |
|---|---|
| ARP | `arp` |
| ICMP | `icmp` |
| TCP | `tcp` |
| UDP | `udp` |
| DNS | `dns` |
| NTP | `ntp` |

## Repository Structure

```text
ethernet-communication-investigation-linux/
│
├── README.md
│
├── docs/
│   └── Ethernet_Communication_Investigation_Report.docx
│
├── screenshots/
│   ├── arp_analysis.png
│   ├── icmp_analysis.png
│   ├── tcp_analysis.png
│   └── udp_analysis.png
│
└── wireshark/
    ├── arp_capture.pcapng
    ├── icmp_capture.pcapng
    ├── tcp_capture.pcapng
    └── udp_capture.pcapng
```

## Results

The investigation demonstrated:

- ARP-based IP-to-MAC address resolution.
- ICMP Echo Request and Echo Reply communication.
- TCP SYN and SYN-ACK packet exchange.
- TCP acknowledgements and TLS application-data packets.
- UDP-based DNS and NTP communication.
- Practical packet inspection using Wireshark.

## Learning Outcomes

- Understanding Ethernet communication fundamentals.
- Knowledge of MAC and IP addressing.
- Understanding TCP/IP protocol behaviour.
- Practical experience with Wireshark.
- Basic Linux network troubleshooting.

## References

- Automotive Communication Networks – Ethernet1 Assignment.
- Wireshark Documentation.
- Linux Networking Manual Pages.
- TCP/IP Protocol Documentation.

**Author:** Monesh M. Borole
