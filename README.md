Project Overview

This project involves designing and implementing a multinational enterprise network for Global Enterprises. The network architecture includes five interconnected sites:

Headquarters (HQ)

Branch Office 1

Branch Office 2

Data Center

Demilitarized Zone (DMZ)

The design focuses on secure connectivity between sites, proper network segmentation, and controlled access to critical services.

##  Topology Map
<img width="600" alt="Global Enterprise Topology" src="https://github.com/user-attachments/assets/0e2870e1-edd0-44a4-a6e2-88c1e9feda74" />

Key Technologies

Networking

OSPF for internal dynamic routing

BGP for inter-domain routing between sites

Security

Access Control Lists (ACLs)

VLAN segmentation for department isolation

Device-level firewall rules

Wireless

WPA2 PSK authentication

Security & IAM Highlights

Least Privilege

Implemented ACL 110 to restrict FTP access to authorised subnets only

Network Segmentation

Separated HR and Finance departments using VLANs to reduce lateral movement risk

DMZ Implementation

Public-facing Web and FTP servers are placed in a DMZ to isolate them from the internal Data Center

Learning Outcomes

Design secure enterprise network architectures

Implement routing protocols for multi-site environments

Apply segmentation and access control to reduce attack surface

Deploy DMZ architecture for external-facing services
