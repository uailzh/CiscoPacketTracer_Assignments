Cisco Packet Tracer Assignments

Overview

This repository contains a collection of Cisco Packet Tracer assignments showcasing my ability to design, implement, and troubleshoot various network setups and scenarios. These assignments cover a range of networking concepts including:

Setting up connections
Configuring FTP and DNS servers
Implementing APIPA (Automatic Private IP Addressing)
Configuring VLANs (Virtual Local Area Networks)
Implementing dynamic and static routing
Facilitating communication between different networks
Assignments

Assignment 1
Purpose: 
The purpose of this assignment is to set up and configure network with two VLANs that are connected by two routers and establish inter-VLAN communication for devices.

Equipment:
•	Two Switches (S0 and S1)
•	Two PCS (PC0, PC1)
•	Three Laptops (L0, L1, L2)
•	One Server (S0)
•	Two Routers (R0, R1)
•	Terminal Emulation Software

Assignment 2: 
Purpose:
The purpose of this assignment is to configure a DHCP server to provide IP address to
three VLANs (VLAN 20 – Sales, VLAN 30 – Marketing, VLAN 40 – Admin). Also, to
establish inter-VLAN communication for devices.

Equipment:
• Three Switches (S0 and S1, S2)
• 15 PCS (PC0, PC1…..PC14)
• One Server (S0)
• One Routers (R0)
• Terminal Emulation Software

Assignment 3
Purpose:
The purpose of this assignment is to configure DNS server, so that domain it
introduces proper name resolution for the DHCP and DNS server itself; and to three
PCs in VLANs (VLAN 20 – Sales, VLAN 30 – Marketing, VLAN 40 – Admin).

Equipment:
• Three Switches (S0 and S1, S2)
• 15 PCS (PC0, PC1…..PC14)
• One DHCP Server (S0)
• One DNS Server(S1)
• One Router (R0)
• Terminal Emulation Software

Assignment 4
The purpose of this assignment is to learn and enhance the ability to use the introduced Wireshark software. Wireshark is used to perform an analysis of transport layer protocols. In this assignment I will do the packet capture and analysis of these packets.

Methodology
Firstly, I have started the Wireshark application and hit start button so that software starts capturing the packets. For this assignment, I have decided to capture the DNS(Domain Name Service) and ICMP protocols.

ICMP is an Internet Control Message Protocol. It is a network layer protocol that reports errors and provides information related to IP packet processing. This protocol is commonly used to ping or traceroute in networking.
It is important to note that there are a lot of listings with different packets that are being captured by Wireshark. Thus, to make it more convenient, the filters are being applied corresponding to the packets that you are trying to catch. 
The process of filtering is simple, the most basic way to apply a filter is by typing into the filter box at the top of the window and clicking Apply (or pressing Enter). 
Hence, these are the filters that are being applied to capture the specified protocol packets:
•	dns
•	icmp

Usage

Each assignment folder contains the necessary Packet Tracer files (.pkt). To view and interact with the assignments, download Cisco Packet Tracer from Cisco's official website.

Feedback and Contact

Feedback and suggestions for improvement are welcome. Feel free to reach out to me via email or LinkedIn for any inquiries or collaborations.
