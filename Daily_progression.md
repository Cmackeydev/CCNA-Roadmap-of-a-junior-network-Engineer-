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
Everything worked properly after configuring the dns-server in the dhcp pool. I will explain more the lab in the section 4.3

Tomorrow i plan to do some ospf labs so i can pursue with the ipv6 part of the books.

## 12/28/2024

So i did the ospf lab , not the greatest topology but i try to put a lot of routers to experiment OSPF.

## 12/29/2024

Today i started to read the ospfv6 parts of the books. I didn't do a lot of readings today , mainly because i was tired yesterday night i went to a party so , i am waiting for tomorrow to try to compensate.
I am on page 1805/3305 on the first Volume.

## 12/30/2024

Today i continue the reading of the books. Im in the ipv6 parts on page 1905 for now. I plan to do some labs in the courseware part of Boson. (I dont know if i will have time to do all the courseware labs because the importants labs ar the boson labs but i will try to do them both). I want to finish the Coureware parts of Boson before finishing the books. So in the end i will concentrate on Boson labs and Labs that i think of as i do them for now , before doing the practice exams of Boson.

I did one lab of the CCNA courseware. I am now in lab 2.1 ..

## 12/31/2024

Today i continue the IPV6 parts of the book. Im on page 2020 for now.
I plan to do some Boson Courseware lab later in the evening.

I did the Boson courseware lab , and i weird and lucky as i was it was a lab on IPV6 . Loll it was really easy. Tomorrow is the new year but i think i will continue study. I' ll try to stay as consistent as possible

## 1/1/2025

Today was the first day of the year , hopefully for my social life i did nothing on the study today. I was hanging out. I plan to restart tomorrow with some ipv6 labs on my own.

## 1/2/2025

So Today  i did a personnal lab of IPV6 on my own nothing to fancy. I also completed the Module 2 of the Boson vcourseware lab so. I guess we are moving forward.

