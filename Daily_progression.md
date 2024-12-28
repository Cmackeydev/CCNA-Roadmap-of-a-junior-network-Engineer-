# December 2024

## 12/26/2024

I am about to start with yhe IPV6 chapter in the book.
IPV6 being a dense subject i want to first finish a DHCP/DNS lab that i started. The issue is that i am doing the lab and gns3 and i need a dns server.
The solution that i had thought about is this one :  Using a debian package on a virtual machine .
The Virtual machnes that i nstalled on gns3 doesn't come with any package that can act as a dns server so i need to download it , but i cannot connect my topology to access real internet via wireless card and i dont have acces (or rather i dont know) to a wired network whch have access to Internet.
So i must find a wat to modify the qcow2 via qemu (Installing the package on qemu) so that when i use it on gns3 it has a package installed that can act as a dns server. So this s what im working on. I planned to put a screenshot of the topology of the lab  planned to do when  do it.

## 12/27/2024

I gave up on the idea of updating the VM via qemu because of issue setting the connection to wireless network in virt-manager , it seems that it's not feasible.
So i set up the connectipon directly in gns3. The way  does this i used a bridge interface (bridge are quite advanced concpets for the CCNA i'll look for indepthwith them later).
So i used vbr0 i checked on my computer the subnet of the bridge ,  i configure it adress as the default route in my router and then put my debian vps in the same subnet.
I was then able to ping 8.8.8.8 (dns server of google). But it wasn't fully functionnal due to dns issues so as set the dns server of my router as my vps as 8.8.8.8. And Voila everything was *functionnal* (at leat for now). I'll try to finish the (DHCP+DNS) server later.

So i completed the lab. I tried to use bind9 as my dns software , but configuration started to be tricky real fast. Finally i opted for a more *plug and play* solution , dnsmask.
Everything worked properly after configuring the dns-server in the dhcp pool. I will explain more the lab in th section 4.3

Tomorrow i plan to do some ospf labs so i can pursue with the ipv6 part of the books.
