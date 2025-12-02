Retail Store Network Project

This repository contains the Cisco Packet Tracer simulation for a Retail Store Network. The project demonstrates a simple LAN setup including PCs, a printer, a router, a switch, and simulated CCTV devices.

Project Overview

The goal of this project is to design and implement a functional network for a small retail store. The network connects multiple devices to ensure smooth communication, inventory management, billing, and security monitoring.

Tools & Software Used

Cisco Packet Tracer 9.0.0 – To simulate and build the network visually.

Router 2911 (simulated) – To manage network traffic within the LAN.

Switch (simulated) – To connect all devices in one local network.

PCs / Printer (simulated) – Devices for testing connectivity and resource sharing.

Network Topology

Topology Type: Star topology (LAN)
Insert your network screenshot here

Devices
Device Name	Purpose
Manager PC	For managerial tasks and monitoring inventory
Counter PC 1	For billing and sales processing
Counter PC 2	For billing and sales processing
Inventory PC	For stock management
Printer	To print bills, receipts, and reports
Router 2911	To manage routing and IP assignments
Switch	To connect all devices in LAN
CCTV (simulated with PC)	Security monitoring in manager room and counter area
Implementation Steps

Router: Placed first and connected to the switch for central network management.

Cashier PCs: Added two cashier PCs for billing, connected to the switch with IP addresses assigned.

Manager PC: Added for managerial tasks and inventory monitoring, connected to the switch.

Printer: Placed for printing bills and reports, connected to the switch.

Inventory PC: Added to manage stock, connected to the switch.

CCTV (simulated with PCs): Two PCs simulate CCTV monitoring for security, connected to the switch.

Simulation & Testing

Protocol Used: ICMP (IPv4)

Connectivity tested using the ping command between all devices.

All devices responded successfully, confirming proper LAN functionality.
Insert ping screenshot here

Results

Network devices communicate efficiently within the LAN.

ICMP testing confirmed correct IPv4 configuration.

The network supports billing, inventory, printing, and monitoring tasks without issues.

Future Improvements

Integration of actual CCTV devices.

Adding wireless connectivity for mobile devices.

Implementation of VLANs for department-based segmentation.

References

Cisco Networking Academy. “Cisco Packet Tracer.” NetAcad

Cisco Systems. Cisco Packet Tracer Datasheet / User Guide. 2025.

Muhammad, A.A., Abba, K.K., Abubakar, A. “Enterprise Network Design and Implementation using Cisco Packet Tracer.” 2020.

Rakhimov, R.G., Juraev, A.A. “Designing Of Computer Network In Cisco Packet Tracer Software.” Peerian Journal.

Folder Structure
Retail-Store-Network/
│
├─ Topology/           # Cisco Packet Tracer .pkt file
├─ Screenshots/        # Implementation & ping results screenshots
└─ README.md           # Project description and instructions
