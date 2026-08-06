# Multi-Branch WAN Connectivity Using OSPF

## Purpose

Design and implement a scalable multi-branch Wide Area Network (WAN) using OSPF dynamic routing to provide reliable communication between geographically separated branch offices.

---

## Project Description

Designed and implemented a multi-branch enterprise WAN using **Cisco Packet Tracer**, connecting **Bangalore**, **Chennai**, and **Hyderabad** branch offices. Each branch contains an independent Local Area Network (LAN) connected through a Layer 2 switch. The branch routers are interconnected using **Serial DCE/DTE point-to-point links** to simulate WAN connectivity. Configured **OSPF (Open Shortest Path First)** as the dynamic routing protocol to automatically exchange routes between branches, enabling seamless communication across the enterprise network. Network connectivity and routing were verified using **Ping**, **OSPF neighbor verification**, and routing table inspection.

---

## WAN Architecture

This project simulates a multi-branch enterprise WAN where branch offices communicate through dedicated WAN links.

The routers are connected using **Serial DCE/DTE point-to-point links** in Cisco Packet Tracer. These serial links simulate dedicated WAN circuits between branch offices.

In a real-world enterprise environment, organizations usually obtain WAN connectivity from an **Internet Service Provider (ISP)**. The ISP provides technologies such as:

- MPLS VPN
- Leased Lines
- Metro Ethernet
- SD-WAN
- Dedicated Fiber Links

In this project, **MPLS is not implemented** because Cisco Packet Tracer focuses on enterprise network configuration rather than service-provider infrastructure. Instead, **Serial DCE/DTE links represent the WAN circuits provided by an ISP**, allowing the project to demonstrate enterprise routing using OSPF while simulating real-world WAN connectivity.

---

## Technologies Used

- Cisco Packet Tracer
- TCP/IP
- IPv4
- OSPF
- Serial DCE/DTE
- Routing & Switching

---

## Requirements

- Cisco Packet Tracer 8.x or later

> **Note:** This project was designed and tested only in Cisco Packet Tracer.

---

## Skills Covered

- TCP/IP
- OSI Model
- IPv4 Addressing
- Basic Subnetting
- OSPF Configuration
- Dynamic Routing
- WAN Configuration
- Serial Interface Configuration
- Router Configuration
- Switch Configuration
- Enterprise WAN Design
- Network Verification
- Ping
- OSPF Neighbor Verification
- Routing Table Analysis

---

## Project Structure

```text
Multi-Branch-WAN-Connectivity-Using-OSPF/
├── README.md
├── Multi-Branch-WAN-Connectivity-Using-OSPF.pkt
└── screenshots/
    ├── Network-Topology.png
    ├── Router-Verification.png
    ├── Ping-Bangalore.png
    ├── Ping-Chennai.png
    └── Ping-Hyd.png
```

---

## Screenshots

### Network Topology

![Network Topology](screenshots/Network-Topology.png)

---

### Router Verification

Includes:

- OSPF Neighbor Status
- Routing Table
- OSPF Protocol Information
- Interface Status

![Router Verification](screenshots/Router-Verification.png)

---

### Ping Test – Bangalore

![Ping Bangalore](screenshots/Ping-Bangalore.png)

---

### Ping Test – Chennai

![Ping Chennai](screenshots/Ping-Chennai.png)

---

### Ping Test – Hyderabad

![Ping Hyderabad](screenshots/Ping-Hyd.png)

---

## Network Features

- Multi-Branch Enterprise WAN
- OSPF Dynamic Routing
- Area 0 Configuration
- Serial DCE/DTE Point-to-Point WAN Links
- IPv4 Addressing
- Router-to-Router Communication
- LAN-to-LAN Connectivity
- Dynamic Route Learning
- Automatic Route Exchange
- End-to-End Network Communication
- Enterprise WAN Simulation

---

## Verification

The following tests were performed successfully:

- OSPF Neighbor Adjacency Verification
- Routing Table Verification
- OSPF Protocol Verification
- Interface Status Verification
- End-to-End Ping
- Inter-Branch Connectivity Testing

Verification Commands:

```bash
show ip interface brief
show ip ospf neighbor
show ip route
show ip protocols
show running-config
```

---

## Result

Successfully designed and implemented a multi-branch enterprise WAN connecting Bangalore, Chennai, and Hyderabad using OSPF dynamic routing. The branch routers established stable OSPF neighbor relationships and dynamically exchanged routing information over simulated WAN links. End-to-end communication between all branch LANs was successfully verified through Ping, routing table inspection, and OSPF neighbor verification, demonstrating reliable enterprise WAN connectivity.

---

## Software

- Cisco Packet Tracer 9.x (Compatible with 8.x or later)
