## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 27.10.2026		

# Objective :

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required :
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram :

Insert the network topology from Packet Tracer (Screenshot or drawing)

<img width="1916" height="1076" alt="Screenshot 2026-10-27 172626" src="https://github.com/user-attachments/assets/30864d81-b400-4e99-99e0-bfe8eb7a9124" />


________________________________________
# IP Addressing Table (if applicable) :
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure :
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any) :

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results) :

Insert screenshots showing ping success, configuration, or simulation results.

## CONFIGURATION : 

PC1

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/0529901e-84f2-4da7-a31b-ac46b84137f9" />



PC2
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c81b4399-cfe6-483f-9d5d-24218f024aa9" />


SWTICH

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e99ba7bb-2133-49d9-8daa-1ae8f15816b3" />



## PING :

PC1

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/10da13ee-ff60-4a41-8211-0c93e717c73f" />






PC2
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d8dd39b7-82d2-496b-9a80-450e299f510c" />




________________________________________
# Result :
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
