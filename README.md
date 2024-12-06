# IP-Telephony-VoIP-and-Dial-Peering-Networking-Project


## Overview
The project focuses on designing and implementing a **VoIP (Voice over IP) network** for **Turtle Consultancy Limited**, a company providing IT infrastructure solutions. The task was to build a scalable and efficient network to support voice and data communication across four departments: **Finance**, **HR**, **Sales**, and **ICT**.

## Key Features:
- **VoIP Network Setup**: Integrated VoIP services across the network for seamless communication.
- **Cisco Routers and Switches**: Configured **Cisco 2811 routers** for VoIP and **Cisco 2960 switches** for access layer connectivity.
- **IP Addressing**: 
   - **Data Network**: `192.168.100.0/24`
   - **Voice Network**: `172.16.100.0/24`
   - **Router-to-Router Network**: `10.10.10.0/24`
- **VLAN Configuration**: 
   - **VLAN 100** for Voice (VoIP)
   - Data VLANs for each department
- **Inter-VLAN Routing**: Configured **Router-on-a-stick** for routing between voice and data VLANs.
- **Routing Protocol**: Implemented **OSPF** to enable dynamic routing across routers.
- **Security**: Enabled **SSH** for remote access and encrypted all passwords for security.

## Requirements and Configuration:
1. **Network Design**: Used **Cisco Packet Tracer** to design the network with routers, switches, and connected devices (PCs, phones, printers).
2. **DHCP Server**: Configured DHCP for dynamic IP assignment for devices, with separate DHCP configurations for voice and data networks.
3. **Telephony Service**: Set up VoIP services with departmental dial numbers in the format:  
   - Finance (101-199)  
   - HR (201-299)  
   - Sales (301-399)  
   - ICT (401-499)
4. **Dial-Peering**: Configured **dial-peering** on routers for inter-department communication.

## Outcome:
- Connected **80 PCs**, **80 phones**, and **4 printers** across departments, ensuring seamless communication for business operations.
- The project provided hands-on experience in **VoIP technology**, **VLAN management**, **routing protocols**, and **Cisco device configuration**.

## Technologies Used:
- **Cisco 2811 Routers**
- **Cisco 2960 Switches**
- **VLANs & Subnetting**
- **OSPF Routing Protocol**
- **DHCP & VoIP Configuration**
- **SSH for Remote Access**

## Conclusion:
This project enhanced my skills in **enterprise networking**, **VoIP technologies**, and **network security**, allowing me to deliver an optimized, scalable solution for the company's infrastructure.
