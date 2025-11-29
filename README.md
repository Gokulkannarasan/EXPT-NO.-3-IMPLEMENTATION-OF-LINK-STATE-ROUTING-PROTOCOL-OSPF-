# EXPT NO.3 IMPLEMENTATION OF LINK STATE ROUTING PROTOCOL OSPF
# AIM

To connect computers in multiple networks using Open Shortest Path First Routing Protocol and to verify the connectivity between computers.

##  EQUIPMENTS REQUIRED

| S.No | Name                 | Quantity |
|------|----------------------|----------|
| 1    | Desktop Computer     | 4        |
| 2    | Cisco 1800 Router    | 2        |
| 3    | DCE-DTE Cable        | 1        |
| 4    | Cisco 2900 Switch    | 2        |
| 5    | CAT 6 Patch Cable    | 6        |
| 6    | Console Cable        | 2        |

---

## IP ASSIGNMENT

| Name                     | IP Address     | Subnet Mask     | Network      | Class | Gateway        |
|--------------------------|----------------|-----------------|--------------|-------|----------------|
| PC0                      | 192.168.0.1    | 255.255.255.0   | 192.168.0.0  | C     | 192.168.0.200  |
| PC1                      | 192.168.0.2    | 255.255.255.0   | 192.168.0.0  | C     | 192.168.0.200  |
| PC2                      | 192.168.2.1    | 255.255.255.0   | 192.168.2.0  | C     | 192.168.1.200  |
| PC3                      | 192.168.2.2    | 255.255.255.0   | 192.168.2.0  | C     | 192.168.1.200  |
| Router0 FastEthernet0/0  | 192.168.0.200  | 255.255.255.0   | 192.168.0.0  | C     | —              |
| Router0 Serial2/0        | 192.168.1.1    | 255.255.255.0   | 192.168.1.0  | C     | —              |
| Router1 FastEthernet0/0  | 192.168.2.200  | 255.255.255.0   | 192.168.2.0  | C     | —              |
| Router1 Serial2/0        | 192.168.1.2    | 255.255.255.0   | 192.168.1.0  | C     | —              |

---

# NETWORK DIAGRAM
<img width="961" height="1080" alt="Screenshot (361)" src="https://github.com/user-attachments/assets/7c7c1d14-e1e4-4aae-a3a3-ca1d9f7da45d" />



# PROCEDURE
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag two 2900 Switches, two Cisco 1800 Routers, four PC Terminals from tool bar and drop it in work area.
STEP 3: Connect all the PC Terminals and Routers through Switches as shown in the network diagram using CAT 6 Patch cables.
STEP 4: Configure IP address and Gateway in all PC Terminals.
STEP 5: Configure Delhi router IP address, save configuration and restart Delhi router. STEP 6: Configure Chennai router IP address, save configuration and restart Chennai router. STEP 7: Check the connectivity between the computers in network.
STEP 8: Configure OSPF in Delhi router, Save configuration and restart Delhi router.
STEP 9: Configure OSPF in Chennai router, Save configuration and restart Chennai router.
STEP 10: Verify the connectivity between PC Terminals in different networks using Ping command.
STEP 11: Check the routing table in Delhi router and Chennai router using show ip route command

# OUTPUT
![IMG-20251121-WA0013](https://github.com/user-attachments/assets/3936ce71-f270-436d-bf29-2bc9d5b12b0d)




# RESULT
Thus the computers in multiple networks using Open Shortest Path First Routing Protocol is connected and the connectivity between the computers is verified.

