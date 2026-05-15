#Made by Usman ghani,Mujtaba,Ammar <br>
**Project Overview:** Three-Layer Hierarchical Network Design
This project focuses on the architecture and implementation of a professional-grade, three-layer hierarchical network using Cisco Packet Tracer. The design follows the industry-standard Cisco hierarchical model to ensure modularity, scalability, and performance in an enterprise environment.

**Architecture & Design**

The network is logically segmented into three distinct functional zones:

Access Zone (Pink): Functions as the high-density entry point for end-user devices. It leverages DHCP Relay Agents to bridge broadcast domains, ensuring seamless IP assignment from a centralized distribution server.

Distribution Zone (Green): Acts as the policy-based control point for the network. It hosts the primary DHCP server and manages the distribution of services, ensuring efficient data transit to the core backbone.

Core Operations Zone (Blue): Serves as the high-speed transit backbone. It utilizes dynamic routing protocols to maintain low-latency paths and redundant connections between the Access and Distribution layers, preventing single-point-of-failure scenarios.

**Technical Implementation**

The project demonstrates advanced networking competency through the integration of the following protocols:

Dynamic Routing: RIP (Routing Information Protocol) was implemented to ensure automated network path convergence and adaptability.

Automated Services: DHCP relay mechanisms (ip helper-address) were utilized to allow centralized IP management, effectively overcoming the limitations of standard broadcast domains.

Simulation & Testing: The design was validated using Packet Tracer's Simulation Mode, allowing for the observation of ICMP packet transit, verification of routing table updates (show ip route), and confirmation of end-to-end connectivity.

**Future Scalability & Resiliency**

The architecture is designed with a roadmap for enterprise expansion, including:

Secure Connectivity: Plans for IPsec site-to-site VPN implementation to ensure data confidentiality across untrusted backbones.

Mobility: Integration of Wireless LAN Controllers (WLC) and Lightweight Access Points (LAPs) to support a mobile workforce.

High Availability: Proposed implementation of HSRP (Hot Standby Router Protocol) to provide sub-second gateway failover.
