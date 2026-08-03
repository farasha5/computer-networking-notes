# computer-networking-notes
Notes and labs documenting my computer networking learning journey.
# Computer Networking Notes

Welcome! This repository documents my learning of computer networking concepts through notes, diagrams, and practical labs.

## Topics Covered

- OSI Model
- TCP/IP Model
- Network Devices
- IPv4 & IPv6
- Subnetting
- DNS
- DHCP
- HTTP & HTTPS
- Routing
- Switching
- Network Security

## Repository Structure

```
notes/
labs/
images/
```

## Learning Resources

- Cisco Packet Tracer
- Cambridge International AS & A Level Computer Science (9618)

# OSI Model

The OSI model is a conceptual framework that explains how data travels across a network.

| Layer | Name | Example |
|-------|------|---------|
| 7 | Application | HTTP, FTP |
| 6 | Presentation | Encryption |
| 5 | Session | Session management |
| 4 | Transport | TCP, UDP |
| 3 | Network | IP |
| 2 | Data Link | Ethernet |
| 1 | Physical | Cables |

The TCP/IP model (Transmission Control Protocol/Internet Protocol model) is the standard networking model used for communication over the Internet. It consists of 4 layers:

+---------------------------+
| 4. Application Layer       |
+---------------------------+
| 3. Transport Layer         |
+---------------------------+
| 2. Internet Layer          |
+---------------------------+
| 1. Network Access Layer    |
+---------------------------+
1. Application Layer
Provides services directly to user applications.
Combines the functions of the OSI Application, Presentation, and Session layers.
Protocols: HTTP, HTTPS, FTP, SMTP, DNS, SSH
2. Transport Layer
Provides end-to-end communication.
Ensures reliable or fast data delivery.
Protocols:
TCP: Reliable, connection-oriented.
UDP: Faster, connectionless, no guarantee of delivery.
3. Internet Layer
Handles logical addressing and routing of data packets.
Determines the best path for data transmission.
Protocols: IP (IPv4/IPv6), ICMP, ARP
4. Network Access Layer
Handles transmission of data over the physical network.
Includes physical addressing (MAC addresses) and access to the network medium.
Technologies: Ethernet, Wi-Fi, PPP
Data Flow

Application → Transport → Internet → Network Access → Physical Network

TCP/IP vs. OSI Model
TCP/IP Model	OSI Model
Application	Application + Presentation + Session
Transport	Transport
Internet	Network
Network Access	Data Link + Physical

Key points:

TCP/IP has 4 layers.
It is the practical model used on the Internet.
TCP provides reliable communication, while IP handles addressing and routing.
