# 🌐 TryHackMe – Intro to LAN

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen)
![Category](https://img.shields.io/badge/Category-Networking-blue)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📝 Overview

The **Intro to LAN** room introduces the fundamental concepts of **Local Area Networks (LANs)**. It explains how devices communicate within a private network, the role of networking devices, different network topologies, subnetting basics, and essential protocols such as **ARP** and **DHCP**.

These networking fundamentals are essential for anyone pursuing **Cybersecurity, Penetration Testing, Red Teaming, or Network Administration**.

---

# 🎯 Learning Objectives

After completing this room, I learned:

- Understanding Local Area Networks (LAN)
- Router vs Switch
- Bus and Star Network Topologies
- Network Addressing
- Host Address vs Network Address
- Default Gateway
- Introduction to Subnetting
- MAC Address vs IP Address
- ARP Protocol
- DHCP Protocol
- DHCP DORA Process

---

# 🌍 What is a LAN?

A **Local Area Network (LAN)** is a network that connects devices within a limited geographical area such as:

- Home
- School
- Office
- Company

LANs provide:

- High-speed communication
- File sharing
- Printer sharing
- Internet access
- Resource sharing

---

# 🖥️ Network Devices

## Router

A Router connects different networks together.

### Responsibilities

- Routes packets between networks
- Connects LAN to the Internet
- Uses IP Addresses
- Works on OSI Layer 3 (Network Layer)

---

## Switch

A Switch connects multiple devices inside the same LAN.

### Responsibilities

- Uses MAC Addresses
- Sends frames only to the correct device
- Reduces unnecessary traffic
- Works on OSI Layer 2 (Data Link Layer)

---

# 📊 Router vs Switch

| Router | Switch |
|---------|---------|
| Connects Networks | Connects Devices |
| Uses IP Address | Uses MAC Address |
| Layer 3 | Layer 2 |
| Routes Packets | Forwards Frames |

---

# 🌐 Network Topologies

## ⭐ Star Topology

All devices connect to a central switch.

### Advantages

- Easy to manage
- Easy to expand
- One device failure doesn't affect others
- Most common topology today

### Disadvantages

- Switch failure brings down the network

---

## 🚌 Bus Topology

All devices share one backbone cable.

### Advantages

- Low cost
- Simple installation

### Disadvantages

- Backbone cable failure stops the network
- High collision rate
- Difficult troubleshooting

---

# ✂️ Subnetting Basics

Subnetting is the process of dividing one large network into multiple smaller networks.

Benefits include:

- Better organization
- Reduced broadcast traffic
- Improved performance
- Easier network management

### Important Terms

| Term | Description |
|------|-------------|
| Network Address | Identifies the network |
| Host Address | Identifies a device |
| Default Gateway | Router used to access other networks |

---

# 📍 MAC Address vs IP Address

| MAC Address | IP Address |
|-------------|------------|
| Physical Address | Logical Address |
| Permanent | Can Change |
| Layer 2 | Layer 3 |
| Used by Switch | Used by Router |

---

# 🔄 ARP (Address Resolution Protocol)

ARP resolves an **IP Address** into a **MAC Address** inside a local network.

### ARP Process

1. Device sends an ARP Request (Broadcast)
2. Target device replies with its MAC Address
3. Communication begins

---

# ⚡ DHCP (Dynamic Host Configuration Protocol)

DHCP automatically assigns:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server

without manual configuration.

---

# 🚀 DHCP DORA Process

| Step | Packet | Purpose |
|------|--------|----------|
| 1 | Discover | Client searches for DHCP Server |
| 2 | Offer | Server offers an IP Address |
| 3 | Request | Client requests the offered IP |
| 4 | ACK | Server confirms the lease |

---

# 📚 Key Terms

| Term | Description |
|------|-------------|
| LAN | Local Area Network |
| Router | Connects Networks |
| Switch | Connects Devices |
| Subnetting | Dividing Networks |
| ARP | IP → MAC Resolution |
| DHCP | Automatic IP Assignment |
| MAC Address | Physical Address |
| IP Address | Logical Address |
| Default Gateway | Router Interface |

---

# 🔐 Security Relevance

Understanding LAN networking is a critical skill in cybersecurity.

The concepts covered in this room directly support:

- Network Enumeration
- Internal Penetration Testing
- Active Directory Assessments
- ARP Spoofing
- ARP Poisoning
- Man-in-the-Middle (MitM) Attacks
- DHCP Starvation Attacks
- Rogue DHCP Detection

Strong networking knowledge makes vulnerability discovery and exploitation significantly easier during security assessments.

---

# 🚩 Task Answers

## Task 1

| Question | Answer |
|----------|--------|
| LAN stands for | Local Area Network |
| Router's job | Routing |
| Device connecting LAN devices | Switch |
| Cheap topology | Bus Topology |
| Expensive topology | Star Topology |
| Lab Flag | THM{TOPOLOGY_FLAWS} |

---

## Task 2

| Question | Answer |
|----------|--------|
| Dividing networks | Subnetting |
| Subnet Mask Bits | 32 |
| Octet Range | 0–255 |
| Network Identifier | Network Address |
| Device Identifier | Host Address |
| Sends traffic outside LAN | Default Gateway |

---

## Task 3

| Question | Answer |
|----------|--------|
| ARP | Address Resolution Protocol |
| Broadcast Packet | Request |
| Physical Address | MAC Address |
| Logical Address | IP Address |

---

## Task 4

| Question | Answer |
|----------|--------|
| First DHCP Packet | Discover |
| Third DHCP Packet | Request |
| Final DHCP Packet | ACK |

---

# 🎯 Key Takeaways

- LAN connects devices within a limited area.
- Routers connect networks using IP addresses.
- Switches connect devices using MAC addresses.
- Star Topology is the most common LAN design.
- Bus Topology is inexpensive but less reliable.
- Subnetting improves network organization and efficiency.
- ARP maps IP Addresses to MAC Addresses.
- DHCP automates network configuration using the DORA process.

---

# 🏁 Conclusion

The **Intro to LAN** room provides the networking foundation required for future cybersecurity learning.

Understanding **network communication**, **addressing**, **ARP**, **DHCP**, and **subnetting** is essential before moving into topics such as **Web Application Security**, **Network Enumeration**, **Active Directory**, and **Red Team Operations**.

---

## ⭐ Difficulty

**Easy (Beginner)**

---

## 🏷️ Tags

```text
Networking
LAN
Subnetting
ARP
DHCP
MAC Address
IP Address
Topologies
TryHackMe
Cybersecurity
Pre Security
```
