# Cisco-VLAN-and-Inter-VLAN-Routing-Configuration
A Cisco network setup with VLANs and Inter-VLAN routing! 🚀 This config enables VLAN segmentation on a switch and seamless communication via a router using **802.1Q encapsulation**. Perfect for labs, Packet Tracer, or real-world deployments! 🔥
# Cisco VLAN and Inter-VLAN Routing Configuration

## Description
This repository contains the configuration files for a Cisco switch and router setup with VLANs and Inter-VLAN routing. The switch is configured with VLAN 10 and VLAN 20, with access and trunk ports, while the router is configured to route traffic between these VLANs using subinterfaces.

## Network Setup
- **Switch:** VLAN 10 and VLAN 20 configured, trunking enabled.
- **Router:** Subinterfaces configured for VLAN 10 and VLAN 20.
- **IP Addressing:** 
  - VLAN 10: `192.168.1.62/26`
  - VLAN 20: `192.168.1.126/26`
  
## Files
- `switch_config.txt` – Configuration for the Cisco switch.
- `router_config.txt` – Configuration for the Cisco router.
  
## How to Use
1. Apply the switch configuration to a Cisco switch.
2. Apply the router configuration to a Cisco router.
3. Connect the switch to the router using a trunk link.
4. Ensure hosts in VLAN 10 and VLAN 20 can communicate via the router.

## Author
- **Kaushalya Jayasekara**
