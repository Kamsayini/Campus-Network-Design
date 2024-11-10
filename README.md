# University Network Design Project

## Aim/Objective
To design a computer network for the University buildings with optimal use of network IP addresses. The available IP address range is `10.20.0.0/16`.

## Network Design Overview
The network design follows a 3-tier architecture:
- **Core Layer:** Router
- **Distribution Layer:** Multilayer Switch
- **Access Layer:** Switches and End Devices

### Key Considerations
- **Scalability:** Ability to accommodate future growth.
- **Resilience:** Tolerance to faults.
- **Manageability:** Ease of managing devices.

## Network Components

### IT Centre Block
- **Director Office:** 2 Desktop Computers
- **Network Manager Room:** 1 Desktop Computer
- **Technical Officers Rooms:** 2 rooms with 1 computer each
- **Staff Office:** 5 Computers
- **Meeting Room:** 2 Data Points (Video Conference and Computer)
- **Lobby Area:** Wi-Fi Coverage
- **Computer Labs:** 1 & 2 with 60 Computers each
- **Digital Learning and Media Centre:** 30 Computers + 1 Printer
- **Printing Room:** 2 Network Printers

### Department Block
- **Lecture Halls:** 4 Halls with 1 Desktop Computer and 1 Projector each
- **Staff Rooms:** 14 rooms with 1 Desktop Computer each
- **Technical Officers Rooms:** 4 rooms with 1 Computer each
- **Department Meeting Room:** 2 Data Points + Wi-Fi Coverage
- **Computer Labs:** 1 & 2 with 50 Computers each
- **Network Engineering Lab:** 10 Computers
- **Microprocessor Lab:** 12 Computers
- **Computer Vision and Machine Learning Lab:** 50 Computers
- **Department Office:** 2 Computers + 1 Printer

### Access Restrictions
- Computers in the staff room and department office have restricted access for security reasons.
- Printers are accessible only by designated staff.

## VLAN Configuration
Details of VLAN segments, installed devices, allocated sizes, network IDs, IP address ranges, and subnet masks are documented in the assignment.

## Implementation Details
- **Router and Switch Configuration:** Instructions for configuring routers and switches.
- **Wi-Fi Configuration:** Guidelines for setting up wireless access.

## Discussion
This is just a sample of network configurations.This kind of network setup minimizes costs by using the fewest number of switches and routers while ensuring adequate transmission speeds through strategic configuration.

## Conclusion
The designed network meets the needs of the university while adhering to best practices in network architecture and security.
