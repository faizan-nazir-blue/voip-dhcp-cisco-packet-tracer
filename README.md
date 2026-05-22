# VoIP Network with DHCP Configuration using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates a basic VoIP (Voice over IP) network implementation using Cisco Packet Tracer. The network includes DHCP-based IP allocation, Cisco IP Phones, a switch, PCs, and a Cisco router acting as CUCM.

The objective of this project is to understand IP telephony fundamentals, DHCP integration, and enterprise communication network design.

---

## 🖥️ Network Topology

### Devices Used
- Cisco 2811 Router (CUCM)
- Cisco 2960 Switch
- DHCP Server
- Cisco 7960 IP Phones
- PCs

---

## ⚙️ Features

- Dynamic IP allocation using DHCP
- VoIP communication setup
- IP Phone registration
- Centralized switching
- End-device communication
- Enterprise-style network structure

---

## 📂 Project Components

### 1. DHCP Server
Responsible for automatically assigning:
- IP Addresses
- Subnet Mask
- Default Gateway
- VoIP-related network information

### 2. Cisco Switch
Acts as the central communication device connecting:
- Router
- DHCP Server
- IP Phones
- PCs

### 3. IP Phones
Cisco 7960 IP Phones are used for VoIP communication and receive IP addresses dynamically.

### 4. PCs
Connected through IP Phones for end-user access and testing.

---

## 🔄 Working Flow

```text
DHCP Server
     ↓
IP Address Assigned
     ↓
IP Phone Boots
     ↓
Phone Registers with CUCM
     ↓
VoIP Communication Established
```

---

## 🧠 Concepts Covered

- VoIP Basics
- DHCP Configuration
- IP Telephony
- Switching
- Network Communication
- Cisco Packet Tracer
- Enterprise Networking

---

## 🌍 Real-World Relevance

VoIP infrastructures are widely used in:
- Enterprises
- Offices
- Call Centers
- SOC/NOC Environments
- Corporate Communication Systems

This project also helps in understanding how modern communication systems operate over IP networks.

---

## 🔐 Security Perspective

From a SOC perspective, VoIP networks may require monitoring for:
- Unauthorized device registration
- SIP-based attacks
- DHCP misuse
- Network anomalies
- Traffic analysis

---

## 🚀 Future Improvements

- Voice VLAN Configuration
- QoS Implementation
- SIP Configuration
- ACL Security
- CME Integration
- Wireshark Packet Analysis

---

## 🛠️ Tools Used

- Cisco Packet Tracer

---

## 📸 Topology Screenshot

Add your topology screenshot inside the `screenshots/` folder.

---

## 📁 Project File

The Packet Tracer project file is available inside the `project-file/` directory.

---

## 👨‍💻 Author

Faizan Dar

Cybersecurity & SOC Learning Journey
