# 3.IP Connectivity

## 3.4 Single Area OSPF

So the first version of the lab that i did have 8 routers. I didn't put any route redundancy for now , i plan to add later to complexify the topology.
I configured point-to-point network links on all the WAN link and a broadcast-network between the core routers i connected all the interfaces on a /25
subnet and connected them to a switch (just for the purpose of experimentation). I didn't use a lot of OSPF features on this lab , i used passive interface
and network type. Also i expereimented advertising on a per interface activation via `ip ospf process_id area area_id` instead on activating them 
via the `network subnet_id wildmask area area_id` because i dont really like calculatin wildmask and also i didn't use to activate them direclty on the interface.
I will share the topology in `Topology/OSPF_lab_1.png`.

I plan to complexify the topology for a next lab.

## 3.5 FHRP

I did a simple HSRP lab. I got stuck i used different groups on the routers so it didnt work at first. I will put the topology in `Topology/HSRP_lab_1.png`. Always to remember to put the router in the same group.
Otherwise they wont synchronize.