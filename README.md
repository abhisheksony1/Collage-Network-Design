# College Network Design & Simulation

This repository contains a comprehensive hierarchical network design for a multi-department college campus. The project is simulated using **Cisco Packet Tracer** and focuses on high availability, scalability, and robust security.

## 🚀 Key Features

* **Hierarchical Architecture:** Implements the Cisco Three-Tier model (Core, Distribution, and Access) to ensure organized traffic flow and easy expansion.
* **VLAN Segmentation:** Logical separation of campus departments (e.g., Administration, Engineering, Library, and Student Wi-Fi) to enhance security and reduce broadcast domains.
* **Inter-VLAN Routing:** Seamless communication between departments configured via Layer 3 switching and Router-on-a-Stick.
* **Dynamic IP Addressing:** Automated IP management using a centralized **DHCP Server** for all VLANs.
* **Wireless Infrastructure:** Integration of a Wireless LAN Controller (WLC) and Lightweight Access Points to provide campus-wide Wi-Fi.
* **Security & Optimization:** * Standard and Extended **ACLs** for traffic regulation.
    * **NAT/PAT** for internet connectivity.
    * **STP & EtherChannel** for redundancy and link aggregation.

## 🛠️ Technologies & Protocols

| Category | Protocols / Tools |
| :--- | :--- |
| **Simulation** | Cisco Packet Tracer |
| **Routing** | OSPF, Static Routing |
| **Switching** | VLANs, VTP, STP, EtherChannel, 802.1Q |
| **Services** | DHCP, DNS, HTTP (Web Server), Email |
| **Security** | ACLs, NAT/PAT, Firewall |

## 📊 Network Topology
*(Upload your topology screenshot to the repository and link it here)*
![Network Topology Screenshot](https://raw.githubusercontent.com/abhisheksony1/Collage-Network-Design/main/topology_screenshot.png)

## 📁 Project Structure

* `*.pkt`: The main Cisco Packet Tracer simulation file.
* `/Documentation`: IP addressing schemes and configuration logs.
* `/Screenshots`: Evidence of successful connectivity tests (Pings, Traceroutes).

## ⚙️ How to Run
1.  Ensure you have [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) installed.
2.  Clone this repository:
    ```bash
    git clone [https://github.com/abhisheksony1/Collage-Network-Design.git](https://github.com/abhisheksony1/Collage-Network-Design.git)
    ```
3.  Open the `.pkt` file in Packet Tracer.
4.  Allow a few moments for the spanning-tree protocols to converge (green lights) and begin testing.

---
**Author:** [Abhishek Kumar Soni](https://github.com/abhisheksony1)
