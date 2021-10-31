# Enterprise_Network
A complete network layout of a sample company using routers, switches and servers, configured using Cisco Packet Tracer.

Here, an enterprise network is created and interfaced with the given ISP connection. The ISP provided the enterprise an IP address range starting with 202.195.32.0/24, to form 2 virtual networks A (30 hosts) and B (30 hosts) as well as 2 physical networks C (60 hosts) and D (12 hosts) with a default link pairing the ISP router and the Enterprise router.

DHCP servers are installed in networks A, B and C for dynamic allocation of IP addresses, while network D had static IP allocation. Dynamic routing protocol is used for routing within the enterprise network. Network D is used to host the HTTP, FTP and DNS servers of the entire network.

Certain restrictions are enforced on the hosts of network A, where they are not allowed to leave the network, whilst hosts of network B should not be able to access the ISP server. Network C is allowed to connect to the internet through ISP but is disallowed to access the combined HTTP & FTP server of network D.  
