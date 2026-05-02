### **Description**
This is a beginner-level networking project built in Cisco Packet Tracer. The lab demonstrates fundamental Layer 2 connectivity by connecting two PCs to a Cisco 2960 switch using straight-through Ethernet cables.

Both end devices were assigned static IP addresses in the same subnet, and connectivity was verified using the `ping` command. The project also covers viewing the switch's MAC address table to confirm that the switch learned the MAC addresses of both PCs.

### **Key Concepts Covered**
1. Basic switch operation and frame forwarding
2. IP addressing and subnetting
3. Using ICMP ping to test connectivity
4. Verifying Layer 2 communication with `show mac address-table`

### **Tools Used**
- Cisco Packet Tracer 8.2.1
- Cisco 2960 Switch
- Windows PCs

### **Purpose**
To understand how switches build MAC tables and how devices on the same LAN communicate. This is the foundation for all future networking labs like VLANs and routing.

### **How to Run**
1. Download `SWITCH TO END DEVICES.pkt`
2. Open in Cisco Packet Tracer 8.2.1+
3. PC0 → Desktop → Command Prompt → `ping 192.168.1.3`
