# Cisco Packet Tracer Network Project

## Project Overview
This project demonstrates a fully simulated network topology using **Cisco Packet Tracer**. The network includes multiple devices such as **routers, switches, and PCs**, configured to simulate a realistic networking environment. The goal is to understand and implement network design, device configuration, and communication verification.

The topology was designed according to the assignment specifications of **[GIFT University]**, and all configurations were done using **Cisco Packet Tracer commands**.

---

## Network Topology
The network consists of:

- **Routers** – for inter-network communication and routing.
- **Switches** – for local network (LAN) connectivity.
- **PCs / End Devices** – to test connectivity and simulate clients.
- **Connections** – using Copper Straight-Through and Cross-Over cables depending on device type.

The project demonstrates:
- Network segmentation using subnets
- Inter-VLAN communication 
- Routing using static routes
- Device-to-device communication testing using `ping`

# PASTE HERE THE SCREENSHOT OF TOPOLOGY 

---

## Functionality
This project allows you to:

1. **Device Configuration**
   - Assign IP addresses and subnet masks
   - Configure default gateways
   - Set up hostnames for routers and PCs

2. **Network Verification**
   - Test connectivity between devices using `ping`
   - Verify routing tables and interfaces on routers
   - Ensure all devices are reachable within the network

3. **Command Line Operations**
   All configuration was done using Cisco Packet Tracer CLI commands such as:
   ```bash
   Router> enable
   Router# configure terminal
   Router(config)# hostname R1
   Router(config)# interface GigabitEthernet0/0
   Router(config-if)# ip address 192.168.1.1 255.255.255.0
   Router(config-if)# no shutdown
   Router(config-if)# exit
   Router(config)# ip route 192.168.2.0 255.255.255.0 192.168.1.2
   Router# ping 192.168.2.1
## Author
Fatima Sohail BS Data Science

⭐ This project is developed as part of a Computer Network course.
