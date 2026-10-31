VLAN AND VTP NETWORK CONFIGURATION
===================================

PROJECT OVERVIEW
----------------
Designed a switching network using VLAN segmentation and VLAN Trunking
Protocol (VTP) in Cisco Packet Tracer.

The project demonstrates VLAN creation, access-port assignment, VTP
operating modes, and trunk connections between switches.

NETWORK TOPOLOGY
----------------
The network consists of:
- 4 Cisco 2960 switches
- 4 PCs and 2 laptops
- 3 VLANs

SWITCH CONFIGURATION
--------------------
- Switch0 (S1): VTP Server
- Switch1 (S2): VTP Transparent
- Switch2 (S3): VTP Client
- Switch3 (S4): VTP Client

VLAN CONFIGURATION
------------------
VLAN 10 - Students: PC0 and PC1
VLAN 20 - Staff: PC2 and Laptop0
VLAN 30 - HOD: Laptop1 and PC3

NETWORK CONNECTIVITY
--------------------
- All six end devices are connected to Switch0.
- Switch0 is connected to Switch1 through a trunk link.
- Switch1 connects to Switch2 and Switch3 through separate links.
- VTP is used to demonstrate VLAN management and advertisement
  forwarding across the switching network.

TECHNOLOGIES USED
-----------------
- Cisco Packet Tracer
- VLAN Segmentation
- VTP Server, Client, and Transparent Modes
- Trunk Configuration
- Access Port Configuration
- Cisco IOS CLI

PROJECT STRUCTURE
-----------------
packet-tracer/  - Cisco Packet Tracer project file
topology/       - Network topology diagram and description
configurations/ - Switch configuration files
verification/   - Verification screenshots and command outputs

AUTHOR
------
Malik Sayyad

