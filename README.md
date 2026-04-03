# networking_project
This project provides a comprehensive guide to configuring RIP, OSPF, and VLANs within a network infrastructure. It covers the fundamental setup, routing logic, and segmentation techniques required to build a functional, scalable network.

Project Overview
The objective is to demonstrate how to manage internal traffic and inter-departmental communication using three core networking technologies:

1. Virtual Local Area Networks (VLANs)
VLANs are used to segment a physical network into multiple logical networks. This improves security and reduces broadcast traffic.
• Key Focus: Assigning ports to specific VLANs and configuring 802.1Q trunking to allow traffic to flow between switches.

2. Routing Information Protocol (RIP)
RIP is a distance-vector routing protocol used for smaller, simpler networks.
• Key Focus: Configuring the router rip command, enabling Version 2 for classless routing, and advertising local networks using the hop-count metric.

3. Open Shortest Path First (OSPF)
OSPF is a link-state routing protocol designed for larger, more complex enterprise networks.
• Key Focus: Defining Areas (e.g., Area 0), establishing neighbor relationships, and utilizing the Shortest Path First (SPF) algorithm to determine the most efficient route based on bandwidth.

Implementation Goals
• Layer 2 Isolation: Ensuring different departments stay on their own broadcast domains via VLANs.
• Dynamic Routing: Automating the exchange of routing tables between routers using RIP and OSPF.
• Inter-VLAN Routing: Using a "Router-on-a-Stick" or Layer 3 switch configuration to allow communication between segmented groups.

Note: While RIP is excellent for its simplicity, this project highlights OSPF as the more robust solution for modern environments due to its faster convergence and better scalability.
