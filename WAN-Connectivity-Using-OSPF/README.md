# Multi-Branch WAN Connectivity Using OSPF

## Purpose

The purpose of this project is to design and implement a scalable multi-branch Wide Area Network (WAN) using **OSPF (Open Shortest Path First)** dynamic routing. The project demonstrates how geographically separated branch offices can communicate efficiently through dynamically learned routes over simulated WAN links in Cisco Packet Tracer.

---

## Project Description

This project simulates a multi-branch enterprise network connecting **Bangalore**, **Chennai**, and **Hyderabad** branch offices using **Cisco Packet Tracer**.

Each branch consists of:

- One Router
- One Layer 2 Switch
- One Local Area Network (LAN)

The branch routers are interconnected using **Serial DCE/DTE point-to-point links**, representing dedicated WAN circuits. **OSPF Area 0** is configured on all routers to dynamically exchange routing information, allowing automatic route learning and seamless communication between all branch networks.

The implementation demonstrates enterprise routing concepts, WAN connectivity, dynamic routing configuration, and network verification techniques commonly used in production environments.

---

# WAN Architecture

This project simulates a real-world enterprise WAN where multiple branch offices communicate over dedicated WAN connections.

The routers are connected using **Serial DCE/DTE point-to-point links** in Cisco Packet Tracer. These serial links emulate leased WAN circuits provided by an Internet Service Provider (ISP).

In real enterprise deployments, organizations typically obtain WAN connectivity using technologies such as:

- MPLS VPN
- Leased Lines
- Metro Ethernet
- SD-WAN
- Dedicated Fiber Links

Cisco Packet Tracer does not simulate service-provider MPLS infrastructure. Therefore, **Serial DCE/DTE links are used to represent ISP-provided WAN circuits**, allowing the project to focus on enterprise routing using OSPF.

---

# Network Topology

```
                WAN
      ------------------------

      Bangalore -------- Chennai
           \                /
            \              /
             \            /
             Hyderabad

      ------------------------

Each Branch

PC(s)
   |
Switch
   |
Router
```

---

# Technologies Used

- Cisco Packet Tracer
- TCP/IP
- IPv4
- OSPF (Area 0)
- Routing & Switching
- Serial DCE/DTE
- WAN Technologies
- Enterprise Network Design

---

# Requirements

- Cisco Packet Tracer 8.x or later

> **Note:** This project was developed and tested using Cisco Packet Tracer 9.x and is compatible with version 8.x or later.

---

# Skills Demonstrated

- Enterprise WAN Design
- TCP/IP Networking
- OSI Model
- IPv4 Addressing
- Basic Subnetting
- Router Configuration
- Switch Configuration
- Serial Interface Configuration
- OSPF Configuration
- Dynamic Routing
- Routing Table Analysis
- Network Troubleshooting
- End-to-End Connectivity Testing
- Ping Verification

---

# Network Features

- Multi-Branch Enterprise WAN
- OSPF Area 0 Configuration
- Dynamic Route Learning
- Automatic Route Exchange
- Router-to-Router Communication
- LAN-to-LAN Connectivity
- Serial Point-to-Point WAN Links
- IPv4 Addressing
- Enterprise Network Simulation
- End-to-End Communication

---

# Project Structure

```text
Multi-Branch-WAN-Connectivity-Using-OSPF/
│
├── README.md
├── Multi-Branch-WAN-Connectivity-Using-OSPF.pkt
│
└── screenshots/
    ├── Network-Topology.png
    ├── Router-Verification.png
    ├── Ping-Bangalore.png
    ├── Ping-Chennai.png
    └── Ping-Hyd.png
```

> **Note:** Ensure the screenshot filenames match the repository exactly.

---

# Screenshots

## Network Topology

Shows the complete enterprise WAN topology connecting Bangalore, Chennai, and Hyderabad branches.

```markdown
![Network Topology](screenshots/Network-Topology.png)
```

---

## Router Verification

Includes:

- OSPF Neighbor Status
- Routing Table
- OSPF Protocol Information
- Interface Status

```markdown
![Router Verification](screenshots/Router-Verification.png)
```

---

## Ping Test – Bangalore

```markdown
![Ping Bangalore](screenshots/Ping-Bangalore.png)
```

---

## Ping Test – Chennai

```markdown
![Ping Chennai](screenshots/Ping-Chennai.png)
```

---

## Ping Test – Hyderabad

```markdown
![Ping Hyderabad](screenshots/Ping-Hyd.png)
```

---

# Verification

The following verification steps were successfully completed:

- OSPF Neighbor Adjacency Verification
- Routing Table Verification
- OSPF Protocol Verification
- Interface Status Verification
- End-to-End Ping Testing
- Inter-Branch Connectivity Verification

---

# Verification Commands

```bash
show ip interface brief

show ip ospf neighbor

show ip route

show ip protocols

show running-config
```

---

# Expected Output

Successful verification should show:

- OSPF neighbors in FULL state
- Dynamically learned OSPF routes
- Active Serial interfaces
- Reachable remote branch LANs
- Successful Ping replies between all branches

---

# Learning Outcomes

This project demonstrates practical experience in:

- Designing enterprise WAN topologies
- Configuring OSPF dynamic routing
- Configuring Serial DCE/DTE interfaces
- Establishing OSPF neighbor relationships
- Troubleshooting routing issues
- Verifying enterprise network connectivity
- Understanding dynamic routing operations

---

# Future Enhancements

Possible improvements include:

- Multi-Area OSPF
- OSPF Authentication
- Route Summarization
- Default Route Advertisement
- Redundant WAN Links
- HSRP
- VRRP
- DHCP Services
- NAT Configuration
- ACL Security
- IPv6 Implementation
- QoS Configuration
- SD-WAN Migration

---

# Software

- Cisco Packet Tracer 9.x
- Compatible with Cisco Packet Tracer 8.x or later

---

# Result

Successfully designed and implemented a scalable multi-branch enterprise WAN connecting **Bangalore**, **Chennai**, and **Hyderabad** using **OSPF Area 0** dynamic routing.

All routers established stable OSPF neighbor adjacencies and dynamically exchanged routing information across simulated WAN links. Complete end-to-end LAN connectivity was verified using ICMP Ping, routing table inspection, OSPF neighbor verification, interface status checks, and routing protocol validation.

The project demonstrates practical enterprise networking concepts including WAN design, dynamic routing, router configuration, troubleshooting, and network verification using Cisco Packet Tracer.

---

# Author

**Yuvasrii**

If you found this project helpful, consider giving it a ⭐ on GitHub.
