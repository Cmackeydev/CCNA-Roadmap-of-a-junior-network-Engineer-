# 1.Network Fundamentals

## 1.9 IPV6

This is a topic that i am not really fund of. Ipv6 came as a solution for ipv4 exhaustion whith 2<sup>128</sup> possible ip Adresses which is a pretty big number. 
Subnetting in IPV6 is pretty much easy compared to IPv4 because they usually used a fixed number of hosts betwwen subnets having each subnet as a /64 subnet.
One of the much new functionnality is the avrious kind of ipv6 adresses. Global Unicast Adress / Unique Local Adress / Link local Adress / Multicast Adress / solicited Multicast Adress which creates a lot of subnet mask to learn for each. One of the great new functionnality of Ipv6 is the Eui-64 for be much more precised the modified eui-64 which permits to generate an ip adress based on just a subnet prefix , that will be completed based upon the mac adress of the interface on the network..

Ipv6 got quite some subtilities. Like Link local Adresses doesnt get added on the routing table. Also because of this when we use Link local Adresses as next hop
we have to specify the interface. So this is some of the nuances that i learned for now. I should do some meticulous lab using Ipv6 to learn more.

I did a lab on Boson classeware and it's was pretty straightforward , configuring link local adresses manually on interfaces nothing much fancy.