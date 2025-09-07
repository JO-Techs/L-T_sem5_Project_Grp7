# ARP LAN Simulation (Cisco Packet Tracer)

## Aim
To construct a simple LAN and understand the concept and operation of the Address Resolution Protocol (ARP) using Cisco Packet Tracer.

## Problem Statement
In a Local Area Network (LAN), devices communicate using MAC addresses at the data link layer, but applications and users work with IP addresses. Address Resolution Protocol (ARP) is used to map an IP address to its corresponding MAC address.  
The task is to design a LAN with multiple PCs connected through a switch and demonstrate how ARP works when one PC communicates with another.

## Scope
- Demonstrates ARP request and reply during communication between PCs.  
- Shows how ARP entries are stored in the ARP table of each PC.  
- Verifies switch MAC address learning.  
- Useful for students and professionals learning computer networks and basic LAN communication.  

## Required Components
### Software
- Cisco Packet Tracer (for simulation)  
- GitHub (for version control and documentation)  
- Screen recorder (OBS Studio or Windows Game Bar)  

### Virtual Hardware (in Packet Tracer)
- 2 or 3 PCs (PC-PT)  
- 1 Cisco 2960 Switch (8-port)  
- Copper Straight-Through LAN Cables  

## Simulated Circuit
The network consists of 2 PCs connected to a switch. Each PC is assigned an IP address in the same subnet.  

- PC1: 192.168.1.1 / 255.255.255.0  
- PC2: 192.168.1.2 / 255.255.255.0  
- (Optional) PC3: 192.168.1.3 / 255.255.255.0  

**Topology Screenshot:**  
*(Insert `screenshots/topology.png` here)*  

## Working and Demonstration
1. Configure IP addresses on each PC.  
2. On PC1, check ARP cache before communication:  
