A trading floor Support centre employs 400 staff. 
They have recently expanded and as a result, 
need to move to a new building. 
A building has been identified but has no network. 
This means that before they can make to move out, 
new network service needs to be designed and 
implemented in the new building. 

Existing Network comprises of the following elements: 

The new building is expected to have four floors with two departments in each for example;
First floor- 
	(Sales and Marketing Department-60 users expected, 
	Human Resource and Logistics Department-60 users expected).
Second floor- 
	(Finance and Accounts Department-60 users expected, 
	Administrator and Public Relations Department-60 users expected).
Third floor- 
	(ICT-60 users expected, Server Room-14 devices expected).
Fourth floor-
	(Research and Development - 60 users expected).

Therefore, as a key member of the Networks Team, 
you have been tasked to design a network for the new building. 
At this stage, logical design is required, 
which shows the measures that you would put in place 
to ensure that the new network meets the current business need and is future-proofed:

Use Cisco Packet Tracer to design and implement the network solution.
	- Use hierarchical model providing redundancy at every layer 
i.e. two routers and two multilayer switches are expected to be used to provide redundancy.


	- The network is also expected to connect to at least two ISPs 
to provide redundancy and each router to the connected to the two ISPs.

	- Each department is required to have a wireless network for the users.

	- Each department should be in a different VLAN and in different subnetwork.
	
	- Provided a base network of 192.168.1.0, carry out subnetting 
to allocate the correct number of IP addresses to each department.

	- The company network is connected to the static, 
public IP addresses (Internet Protocol) 195.136.17.0/30, 195.136.17.4/30, 
195.136.17.8/30 and 195.136.17.12/30 connected to the two Internet providers.

	- Configure basic device settings such as hostnames, console password, enable password, banner messages, disable IP domain lookup.

	- Devices in all the departments are required to communicate with each other with 
the respective multilayer switch configured for inter-VLAN routing.

	- The Multilayer switches are expected to carry out both routing and 
switching functionalities thus will be assigned IP addresses.

	- All devices in the network are expected to obtain an IP address dynamically 
from the dedicated DHCP servers located at the server room.

	- Devices in the server room are to be allocated IP address statically.

	-- Use OSPF as the routing protocol to advertise routes both 
on the routers and multilayer switches.

	-- Configure SSH in all the routers and layer three switches for remote login.

	-- Configure port-security for the Finance and Accounts department 
to allow only one device to connect to a switchport, 
use sticky method to obtain mac-address and violation mode shutdown.

	-- Configure PAT to use the respective outbound router interface IPv4 address, 
implement the necessary ACL rule.

	-- Test Communication, ensure everything configured is working as expected.
	
Technologies Implemented
	Creating a network topology using Cisco Packet Tracer.
	Hierarchical Network Design.
	Connecting Networking devices with Correct cabling.
	Configuring Basic device settings.
	Creating VLANs and assigning ports VLAN numbers.
	Subnetting and IP Addressing.
	Configuring Inter-VLAN Routing on the Multilayer switches (Switch Virtual Interface).
	Configuring Dedicated DHCP Server device to provide dynamic IP allocation.
	Configuring SSH for secure Remote access.
	Configuring OSPF as the routing protocol.
	Configuring NAT Overload(Port Address Translation PAT).
	Configuring standard and extended Access Control Lists ACL.
	Configuring switchport security or Port-Security on the switches.
	Configuring WLAN or wireless network (Cisco Access Point).
	Host Device Configurations.
	Configuring ISP routers.
	Test and Verifying Network Communication.
