# VLAN Configuration using Cisco Packet Tracer

## Overview
This project demonstrates the configuration of Virtual Local Area Networks (VLANs) and Inter-VLAN Routing using the Router-on-a-Stick method in Cisco Packet Tracer.

The objective is to divide a single physical switch into multiple logical networks, improving security, reducing broadcast traffic, and enabling communication between VLANs through a router.

---

##  Objectives

- Create VLAN 10 (HR) and VLAN 20 (Sales)
- Assign switch ports to their respective VLANs
- Configure a trunk link between the switch and router
- Configure Router-on-a-Stick using IEEE 802.1Q encapsulation
- Verify communication within and between VLANs

---

## Software Used

- Cisco Packet Tracer

---

## Network Topology

Devices Used:

- 1 Router
- 1 Switch
- 4 PCs

##  IP Addressing

### VLAN 10

| Device | IP Address | Default Gateway |
|---------|------------|-----------------|
| PC1 | 192.168.1.10 | 192.168.1.1 |
| PC2 | 192.168.1.11 | 192.168.1.1 |

### VLAN 20

| Device | IP Address | Default Gateway |
|---------|------------|-----------------|
| PC3 | 192.168.2.20 | 192.168.2.2 |
| PC4 | 192.168.2.21 | 192.168.2.2 |

---

##  Configuration Performed

- Created VLAN 10 
- Created VLAN 20 
- Assigned access ports to the appropriate VLANs
- Configured a trunk port between the switch and router
- Configured Router-on-a-Stick using IEEE 802.1Q subinterfaces
- Assigned gateway IP addresses to each VLAN
- Tested network connectivity

---

##  Verification

### Before Router Configuration

- Devices within the same VLAN communicate successfully.
- Communication between VLAN 10 and VLAN 20 fails.

### After Router Configuration

- Devices in different VLANs successfully communicate through the router.
- Inter-VLAN routing is verified using successful ping tests.

---

##  Concepts Learned

- Virtual Local Area Networks (VLANs)
- Access Ports
- Trunk Ports
- IEEE 802.1Q (Dot1Q)
- Router-on-a-Stick
- Inter-VLAN Routing
- IP Addressing
- Broadcast Domains

---

##  Repository Contents

- `VLAN.pkt` – Cisco Packet Tracer simulation file
- `README.md` – Project documentation

---

---

⭐ If you found this project useful, feel free to star the repository.
