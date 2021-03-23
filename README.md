# network_project

BNK Bank has 4 branches spread out in the city.
1. Main LA Branch -  Consists of 200 hosts.
2. Riverside Branch - Consists of 100 hosts.
3. Anaheim Branch  - Consists of 120 hosts.
4. Pomona Branch - Consists of 90 hosts.

- Configure VLAN and Inter-VLAN Routing
- Limit telnet access on switches and routers to the administrator Laptop (specify the IP address)
- "The main Branch should have the connection to the ISP for the Internet. 
- It should have redundant connections with the other branches."
- "The bank has an application server, which is used by it’s customers for online transactions and 
a database server which is used by the branches."
- The Internet in this example consists of ONLY 2 servers i.e (Google and Gmail )
- RIPv2 routing protocol should be used between the internal routers and static routing with the ISP router.
- "A static host route should be configured in the ISP for the application server for faster service. 
- The redundant links between branches should serve as back ups."
- Private IP network address used by the bank is 192.168.0.0/16
- Configure a DHCP Server on the internal router to serve all Los Angels’ VLANs
- All the branches should get their IP through DHCP.
- "The ISP has allocated 8 public addresses for this bank, 13.100.96.35 – 42/26.
- The first two addresses are statically allocated for the application server and database server at the main branch."
- All private addresses allocated must be translated to public when accessing the Internet.
- The customers and the main branch should have access to the application server.
- Main branch should have access to the Internet anywhere.
- The other branches are only allowed to access the Gmail server.
- Configure a VPN tunnel between main Los Angeles branch and Riverside branch

