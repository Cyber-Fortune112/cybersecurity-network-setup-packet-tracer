# cybersecurity-network-setup-packet-tracer
Secure Office Network Design Using Cisco Packet Tracer
# Secure Office Network Design Using Cisco Packet Tracer

## Project Overview

This project demonstrates the design and implementation of a secure small office network for approximately 25 employees using Cisco Packet Tracer.

The network was built following cybersecurity best practices, including VLAN segmentation, inter-VLAN routing, trunking, structured IP addressing, and Access Control Lists (ACLs).

---

## Objectives

* Design a secure office network topology.
* Implement VLAN segmentation.
* Configure inter-VLAN routing.
* Secure guest access using ACLs.
* Demonstrate network connectivity.
* Document the implementation.

---

## Technologies Used

* Cisco Packet Tracer 9.0
* Cisco 3560 Multilayer Switch
* Cisco 2960 Switch
* VLANs
* IEEE 802.1Q Trunking
* Inter-VLAN Routing
* IPv4
* Access Control Lists (ACLs)

---

## Network Topology

*(Insert a screenshot of your topology here after uploading it to GitHub.)*

---

## VLAN Configuration

| VLAN    | Purpose              |
| ------- | -------------------- |
| VLAN 10 | Employees            |
| VLAN 20 | Servers and Printers |
| VLAN 30 | Guest Network        |
| VLAN 40 | Management           |

---

## IP Addressing

| VLAN    | Network         | Gateway      |
| ------- | --------------- | ------------ |
| VLAN 10 | 192.168.10.0/24 | 192.168.10.1 |
| VLAN 20 | 192.168.20.0/24 | 192.168.20.1 |
| VLAN 30 | 192.168.30.0/24 | 192.168.30.1 |
| VLAN 40 | 192.168.40.0/24 | 192.168.40.1 |

---

## Security Features

* VLAN segmentation
* Inter-VLAN routing
* Extended ACLs
* Guest network isolation
* Dedicated management VLAN

---

## Project Validation

The following tests were successfully completed:

* VLAN verification
* Trunk verification
* Inter-VLAN routing
* End-to-end connectivity testing
* ACL configuration

---

## Repository Contents

```text
packet-tracer/
topology/
docs/
README.md
```

---

## Author

**OLUWATOSIN FAWOLE**

Cybersecurity Student | Network Security | SOC Analyst
