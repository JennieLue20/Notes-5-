# Notes-5-
Networking &amp; Content Delivery 
//Overview
Basic networking needs a switches or router to communicate with other devices.
Each network has its own custom IP Address. There are different types of IP Address:
1. IP Address = 32 bits in binary format
2. IPV4 = 32 bits
3. IPV6 = 128 bits each group contains 16bits
//quote
"Routers work at layer 3, hubs and switches work at layer 2 link"
Since the network layer is aware of the addresses of nearby network nodes, 
it is in charge of packet forwarding, including routing through intermediate routers.
Amazon VPC= Vitural Private Cloud
Gives you control of vitrual networking, you can also customize IP address and network configuration.
VPC is isolated, can only control all VPC on a private region.
//quote
"Before creating VPC you must assign a custom IP address" 
When creating an IP address make sure you select the correct size ( small or Large ) 
Also make sure to select public or elastic. 
Public is a manual IP address and Elastic is associated with an account. (Additional cost may varie) 
Elastic Network interfaces attach to an instance. 
Detached from the instances
Route tables control traffic from your subnet. 
Route 53 is the elastic balance to make sure all traffic is flowing. 
//services
Amazon CloudFont- fast global and secure services. ( pay as you go ) 
