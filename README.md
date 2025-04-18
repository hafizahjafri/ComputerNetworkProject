# Network Infrastructure Design for Faculty of Computing (Block N28B)

## 📚 Project Overview
This project designs and implements a complete network infrastructure for the new Faculty of Computing building (Block N28B), a two-floor academic facility with four specialized labs, two video conferencing rooms, and multiple staff rooms. The network ensures high availability, scalability, and security, supporting future expansion.

Developed using Cisco Packet Tracer, the project integrates dynamic routing (EIGRP), static routing (for ISP connection), VLANs for network segmentation, DHCP for automated IP addressing, and a structured subnetting plan.

---

## 🎯 Objectives
- Design and simulate a real-world network topology.
- Implement IP addressing and subnetting for efficient host management.
- Configure dynamic (EIGRP) and static routing for internal and external communications.
- Create VLANs for network segmentation and management.
- Set up DHCP servers for dynamic IP allocation.
- Ensure full end-to-end connectivity across all labs, rooms, and staff areas.

---

## 🛠️ Tools & Technologies
- Cisco Packet Tracer
- Networking Protocols:  
  - EIGRP (Enhanced Interior Gateway Routing Protocol)  
  - Static Routing
  - VLANs
  - DHCP
- IP Subnetting (CIDR / VLSM)

---

## 🏩 Building Layout
- **Ground Floor**:
  - IoT Lab (25 Workstations)
  - Network Lab (32 Workstations)
  - Video Conferencing Room 1
- **First Floor**:
  - Computer Security Lab (25 Workstations)
  - General Purpose Lab (31 Workstations)
  - Video Conferencing Room 2
- **Additional Areas**:
  - Staff Room 1 & 2 (Ground Floor)
  - Staff Room 3 & 4 (First Floor)

---

## 🗂️ Repository Structure
```bash
faculty-computing-network-infrastructure/
│
├── README.md
├── floor-plans/
│   ├── ground_floor_plan.png
│   ├── first_floor_plan.png
├── packet-tracer-files/
│   ├── network_topology.pkt
│
├── documentation/
│   ├── IP_addressing_scheme.pdf
│   ├── VLAN_configuration_steps.pdf
│   ├── Routing_protocols_setup.pdf
│   ├── DHCP_configuration.pdf
│
└── reflections/
    ├── lessons_learned.md
```

---

## 📸 Screenshots
<details>
<summary>Click to expand</summary>

| Floor Plans | Network Topology |
|:-----------:|:----------------:|
| ![](floor-plans/ground_floor_plan.png) | ![](packet-tracer-files/network_topology.png) |

</details>

---

## 🔥 Key Highlights
- **Subnetting Strategy**: Carefully designed to optimize address allocation across different labs and rooms.
- **Routing Setup**:  
  - EIGRP dynamic routing among internal networks.
  - Static routing for connecting to the external ISP.
- **VLAN Implementation**: Logical segmentation of staff, labs, and management networks to boost security and traffic management.
- **Dynamic IP Assignment**: Using DHCP to automate workstation IP configuration.

---

## ✨ Lessons Learned
- Mastered advanced IP subnetting techniques for large and diverse network environments.
- Implemented and troubleshooted EIGRP dynamic routing and static routes.
- Gained hands-on experience in VLAN creation, trunking, and inter-VLAN routing.
- Developed critical thinking and troubleshooting skills through live network simulations.

---

> **Developed by:**  
> Hafizah, Nursyuhada, Farah Hazirah, Faiz
