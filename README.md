# Company-Building-Cisco-Packet-Tracer
Network Layout & Segmentation:

  The building has 4 floors with multiple departments on each floor.
  
  Each department must be placed in its own VLAN and assigned a different subnet.
  
  VLANs will isolate traffic by department but must also allow inter-department communication via routing.

IP Addressing & Subnetting:
  
  Use the base network 172.16.1.0 and subnet it to fit the required number of users per department.
  
  Servers in the server room get static IPs.
  
  User devices will get IPs dynamically via DHCP servers located in the server room.

Network Devices & Design:

  Use a hierarchical network model (core, distribution, access).

  Provide redundancy by using:
  
    Two routers connected to two different ISPs for internet redundancy.
    
    Two multilayer switches for internal redundancy and inter-VLAN routing.
    
    Configure multilayer switches to perform both switching (VLANs) and routing (inter-VLAN routing).

Connectivity & Services:
  
  Configure wireless networks for each department with Cisco Access Points.
  
  Use OSPF as the routing protocol to advertise routes across routers and multilayer switches.
  
  Configure SSH on all routers and multilayer switches for secure remote management.

Security:

  Implement port-security on the Finance and Accounts department switches:
    
    Allow only one device per switchport.
    
    Use sticky MAC address learning.
    
    Violation mode should shutdown the port.
    
  Configure PAT (Port Address Translation) on routers for outbound internet traffic, using their respective interface IPs.
  
  Create ACLs (Access Control Lists) to control traffic as required.

Testing & Verification:

  Test connectivity between VLANs, internet access, DHCP address assignment, SSH access, and port-security functionality.
  
  Ensure redundancy works by simulating link failures.
