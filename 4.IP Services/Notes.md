# 4.IP Services

## 4.1 NAT

I did a lab to configure NAT.I use a imple Topology really simple not even routing protocols was used. I will put the topology under `Topology/NAT_lab_1.png`.
I used static Nat then Dynamic Nat then PAT. Try to remember when you have to remove a NAT , you have to first clear the Ip translations.

## 4.3 DNS / DHCP

I did a lab to review the DNS protocols as the DHCP features. i went simple on this one no vlans / no centralized dhcp server just a centralized dns server.
I had two subnets on two different routers (Access Network) connected to a core nrouter which contain the third subnet for the servers. I configured a dhcp pool on each access router (excluding some ip in the begeniing of the ranges and configured the dns ip). I will put the topology used under `Topology/`
Some things i dont really understand it's the impact of the domain-name on the routers on the dns-server confgurations. I dont know (like the hostname shouldn't be terminated by the domain name ??) i' ll look n depth on this later.
