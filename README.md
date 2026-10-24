# Enterprise Network Troubleshooting Lab

**Author:** Mohammad Rameez  
**Platform:** Cisco Packet Tracer

## Project Overview
This project demonstrates an enterprise network with VLAN segmentation, inter-VLAN routing, server connectivity, and access control using extended ACLs.

## VLAN and IP Addressing

| VLAN | Purpose | Gateway |
|---|---|---|
| 10 | Corporate | 192.168.10.1 |
| 20 | Guest | 192.168.20.1 |
| 30 | Servers | 192.168.30.1 |
| 99 | Management | 192.168.99.1 |

## Technologies
- Cisco Packet Tracer
- VLANs and 802.1Q trunking
- Router-on-a-stick inter-VLAN routing
- Extended Access Control Lists (ACLs)
- Ping-based connectivity testing

## Security Validation
- Guest-to-Corporate traffic is blocked by an extended ACL.
- Guest-to-Server connectivity is permitted.
- Router VLAN subinterfaces were verified as operational.

## How to Use
1. Download the `.pkt` lab file from this repository.
2. Open it in Cisco Packet Tracer.
3. Inspect the router and switch configurations.
4. Repeat the ping tests to validate connectivity and access restrictions.

## Author
Mohammad Rameez — Network Engineer
