# Small Office VLAN Segmentation

# Objective 
To design and configure a small office network using VLAN segmentation in Cisco Packet Tracer and demonstrate how VLANs can logically separate departments within the same physical network.

# Tools used
CISCO Packet Tracer

# Project Overview
This project simulates a small office network where different departments are separated using VLANs. VLANs were created on the switches, end devices were assigned to their respective VLANs through access ports, and trunk links were configured between switches to allow VLAN traffic across the network.

# Network Setup
The network consists of:
- Cisco 2960 switches(2)
- End devices PCs (6)
- VLANs created for different office departments(VLAN 10-HR, VLAN 20-SALES, VLAN 30-ACCOUNTS)
- Access ports assigned to end devices based on department
- Trunk links between switches for VLAN communication


# Configuration Steps
1. Created VLAN 10, VLAN 20, and VLAN 30 on both switches.
2. Assigned names to the VLANs for easier identification.
3. Configured access ports and assigned them to the correct VLAN.
4. Configured trunk ports between switches to carry VLAN traffic.
5. Verified VLAN configuration using CLI commands.
6. Finally, I tested the connectivity between end devices in the same VLAN.


# Verification Commands
- show vlan brief
- show interfaces trunk


# Results
- VLANs were successfully created and assigned
- Trunk links carried VLAN traffic between switches
- Devices in the same VLAN communicated successfully
- The project demonstrated effective logical segmentation of the network

# Key Learning
This project helped me 
- understand VLAN segmentation
-	access port configuration & trunking between switches, and 
- How basic network segmentation supports better organization and security

# Screenshots
- Network topology
- VLAN creation
- Access port configuration
- Trunk port configuration
- show vlan brief output
- show interfaces trunk output
- Connectivity test

# Author
MADHUMITHA SANYAL
