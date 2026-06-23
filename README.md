# High-Availability Enterprise Network
Built and configured a guided enterprise campus network lab, then troubleshot, validated, and expanded the environment with working DHCP, VoIP, LACP, HSRP, VLAN segmentation, firewall connectivity, and redundant network paths.

# Project Note
The initial design was developed with guidance from a networking tutorial. I configured, tested, troubleshot, and validated the environment to strengthen my network design/troubleshooting skills. 

# Implemented Features
- Redundant ISP connections
- VLAN segmentation
- Inter-VLAN routing
- LACP EtherChannel
- HSRP gateway redundancy
- DHCP service
- Working VoIP phones and voice VLAN configured on CME router
- Wireless (WLC with WLANS - Employees, Guests, Corporate-Exec)
- Firewall and ISP connectivity
- DMZ network segment - Access for configured cloud users. 

# Actions Performed
- Configured and validated VLAN segmentation, inter-VLAN routing, HSRP, LACP EtherChannel, DHCP, VoIP, wireless connectivity, and redundant network paths.
- Troubleshot OSPF routing and adjacency issues to restore dynamic route exchange between network devices.
- Diagnosed and resolved firewall and ISP connectivity problems, including routing, interface configuration, and external reachability.
- Corrected an err-disabled trunk caused by inappropriate PortFast and BPDU Guard settings.
- Tested connectivity between internal networks, the DMZ, firewall zones, ISP infrastructure, and simulated external users.
- Implemented and tested DMZ firewall policies controlling access to authorized resources.
- OSPF router IDs are labeled on each router for easier topology identification and troubleshooting, such as 1.1.1.1 and 2.2.2.2.

# Planned Improvements
Complete configuration of centralized TACACS+ authentication with local fallback 
Pending name resolution verification. 
