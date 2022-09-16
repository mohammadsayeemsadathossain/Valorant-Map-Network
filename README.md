# Valorant-Map-Network
 - Given distances between all the maps in Valorant, I tried to create a Computer Network connecting all the Routers set within the maps in a way that the packet gets transferred taking the shortest route possible.
 - There are six maps as of the initial commit, namely: Bind, Breeze, Split, Ascent, Icebox.
 - The shortest distances to each path is given in the Network Topology Diagram.
 - The assigned IP Addresses are given in the IP Addressing Table, from the corresponding VLSM Subnetting method used, to use the least number of IP Addresses available.
 - A public IP Address was assigned to a Server which has been appointed as the main Server, as of now, from where the Data of all maps are stored.
 - Each Router of each map consisted of at least two hosts, can be a PC/Laptop etc.
 - Successful ping and traceroute commands proved that one host from one map can send a packet to any other hosts of any other maps, for which the routing was successful. 
 - Router commands and configurations are given in the Configuration Commands file. 
