# University-Network-VoIP
# University-Network-VoIP

## Overview
A fully configured VoIP network for ABC University designed 
using Cisco Packet Tracer as part of PUSL3129 - Multimedia over IP.

## Network Architecture
- 4 Faculties + Administration department
- Centralized Server Room (DHCP, DNS, HTTP)
- Core Router connecting all departments

## Features Configured
- VLANs for Data and Voice per department
- Router-on-a-stick Inter-VLAN routing
- OSPF dynamic routing protocol
- Centralized DHCP for data (Server Room)
- Local DHCP for voice (per department router)
- IP Telephony with dial-peers across departments
- SSH remote management on all routers
- DNS and HTTP server configuration

## IP Addressing Scheme
| Network | Subnet |
|---|---|
| Data | 172.16.XX.0/24 |
| Voice | 192.168.XX.0/24 |
| Inter-router | 10.10.XX.0/24 |

## Department Phone Extensions
| Department | Extension Range |
|---|---|
| Faculty of Science | 1xxx |
| Faculty of Engineering | 2xxx |
| Faculty of Business | 3xxx |
| Faculty of Arts | 4xxx |
| Administration | 5xxx |

## Tools Used
- Cisco Packet Tracer
- Cisco IOS
