# Secure Company Network Design and Implementation

**Cisco Packet Tracer**

---

## Project Overview

This project presents the design and implementation of a secure enterprise network using **Cisco Packet Tracer**.
The solution emphasizes **network security**, **high availability**, and **scalability**, incorporating advanced routing, switching, and firewall configurations to deliver a robust and resilient infrastructure.

---

## Key Features and Configurations

### Network Segmentation and Security

* VLAN-based network segmentation with controlled inter-VLAN communication
* Access Control Lists (ACLs) to enforce security policies
* Secure remote device management using SSH
* STP PortFast and BPDU Guard enabled on all access ports

---

## Redundancy and High Availability

* EtherChannel (LACP) for link aggregation between switches
* Hot Standby Router Protocol (HSRP) using dual multilayer switches for gateway redundancy
* Dedicated DMZ zone hosting critical enterprise services:

  * FTP Server
  * Web Server
  * Email Server
  * Application Server
  * NAS Storage

---

## Routing and Firewall Security

* OSPF and static routing for optimized traffic flow
* Cisco ASA Firewall deployment for perimeter security
* Security zones configured with distinct trust levels:

  * Inside
  * DMZ
  * Outside
* Network Address Translation (NAT) for internal and external connectivity
* Firewall inspection policies to regulate traffic flow
* Protection of the Inside zone from unauthorized external access

---

## Infrastructure and Services

* DHCP server for dynamic IP address assignment (excluding servers)
* Wireless network infrastructure using:

  * Wireless Access Points (WAPs)
  * Wireless LAN Controller (WLC)
* VoIP integration with two IP phones per department for enterprise communication

---

## Tools and Technologies Used

* Cisco Packet Tracer (network simulation and implementation)
* Cisco ASA Firewall (security enforcement and traffic inspection)
* Networking technologies and protocols:

  * VLANs
  * OSPF
  * HSRP
  * EtherChannel
  * ACLs
  * DHCP
  * NAT
  * STP

---

## Learning Outcomes

This project reinforced key enterprise networking concepts, including:

* Secure enterprise network design best practices
* Firewall policy implementation and access control
* High availability through redundancy mechanisms
* Efficient routing and traffic optimization using OSPF and static routes

---

## Feedback and Contributions

Feedback and contributions are welcome.
Feel free to open issues for suggestions, fork the repository, or submit improvements via pull requests.

---

## License

This project is licensed under the **MIT License** and is intended for learning and development purposes.

---

## Contact
- **LinkedIn:** [linkedin.com/in/omarelgohary2003](https://www.linkedin.com/in/omarelgohary2003/)
* **Email:** [omarrmgohary@gmail.com](mailto:omarrmgohary@gmail.com)
