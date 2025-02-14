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

## 1/3/2025

Today i did reading. i am on page 2700 now. Yes you heard it 2700. What happened is that in the end on the bok there is a bunch of glossaries and appendix so i skiped them
a lot there are also some exercice i did some , some i will get back to them later.

## 1/4/2025

Today i finished the first volumes. In the rest of paes there was about 3 legacy chapters that i read , one was about troubleshooting LAN another was about VLSM and the
third one was kind of a mix. So i finished the first volume today.  I will try to do a lab and the Boson Coureware , i dont know if i will have time later.

I did the first lab in the module 5. There is no lab for module 3 and 4 and the Boson CourseWare.

## 1/5/2025

Today i didnt do much work. I did a lab on Boson Courseware. It was not a difficult one. The only unusual thing i did was to configure the clock on a Serial interfaces.
And i also routed networks with eigrp (was not so different then our almighty ospf) pretty straightforward. Tomorrow i plan to start reading on the Volume 2 of the book.

## 1/6/2025

I am lazy this week. I did some readinf im on page 129 now

## 1/7/2025

Laziness ... Page 205

## 1/8/2025

I will do some reading today , i will also try to do a Boson CourseWare Lab later. we will see if i make it through. It's almost 5 Pm an i didnt do anythong yet for today.
I did the lab from BosonCourse Ware but did not really read anything aboutpages 220.Yes i know ... i' ll try to get my speed back in the week end.

## 1/9/2025

Today i read about .... 20 pages loll , but hey i did two CourseWare labs so i think its was not so bad at all.. The thing it's alo i in the Wifi part i dont really like
the materials in there but hey i have to study them ...

## 1/10/2025

Today i read , im on page 270.

## 1/11/2025

I am taking a break today. Probaly tomorrow also i have another work to do so ...

## 1/12/2025

Break ...

## 1/13/2025

I read through page 300 today .

## 1/14/2025

Im starting tthis to  get he rythm back today i read through pages 340 and did 5 labs in the Courseware.
I am done with module 6 module 7 is about IP services (NAT/ACL) , this is really great because toorrow i' ll start with chapter related to ACL on the books so .
It seems to me like some of the Boson labs got some little problems in the final expected configurations , i wil tr to nvestiguate  more on this later.

## 1/15/2025

I am in page 412 now. The next Chapter is about basics in ACL i will try to read it tonight. I dont know.

I read the othe chapter i am in page 475 now.

## 1/16/2025

I am on page 550 now. I have read a lot about ACL. I think i am much more confident with ACL now. i will try to do a customized labs on gns3 later.
So i dis the lab it was great now i am really confident with ACL but not only ACL but also with my level as a CCNA aspirant.

## 1/17/2025

I am on page 615 now. The next chapters are about security.I would like to finish with the boson Module COurseWare of Ip Services first before continuing the readings.
I will try to do some Labs of the Courseware later , there is about 4 or 5 labs i would like to do them all today but  i will probably finish them tomorrow. Correction i will do the Module 8 lab first.
I did on lab.

## 1/18/2025

I did all the rest of the labs of module 8 for the Boson CourseWare today.  i am left with two modules to finsh with the Boson CourseWare. I think i will finish them soon.
I'll try to read one chapter of the books later. I think that things are going as planned.For now distraction time , i will watch a tv series.

## 1/19/2025

I read through pages 674 today.

## 1/20/2025

I read another chapter im in pages 735. It was more of a theorical chapter the little amount of practical thing i learned i will apply them in final labs.
I wanna read another chapter tonight i will see if i can make it.
I read another chapter i am in page 780 now.

## 1/21/2025

I finished the chapters about securing a Lan today. I am on page 860 now. I started reading the first chapter about ip services.

## 1/22/2025

The goal for today would be  like to be reach the 1000<sup>th</sup> by the end of the day.

I read two more chapters i am at pages 1015 now. The last chapter i read was about Nat configurations. I would like to do a customized lab about Nat later , but i dont know . i' ll see if i will have time. The goal will be to finished the second book by the end of January so i can focus on Labs and Boson Labs and after to take the Boson Exams.

I was exhausted when i got at home. I did not do the lab , i will try to to them tomorrow.

## 1/23/2025

SO i did the lab. I hope to read at least 50 pages later  , 100 pages would be great , so ill try to get to it.

I am on page 1104 now. I just finished with te chapter about QoS. Nexy chapter is abut FHRP  i hope to finish it tomorrow and do a customized labs about it.

## 1/24/2025

I finished the chapter on FHRP. im on page 1150 now. The actual version of CCNA does not focus on FHRP configuration. But i will still do a simple lab.
I will use HSRP as the protocol on my simple lab. I ' ll try to quickly finish the lab so i can continue to read hope to get to pages 1200 today.

I did the lab a simple one as usual.

## 1/25/2025

Did nothing today. tried to read but didn't.

## 1/26/2025

Today i finish the chapter on snmp and FTP and TFTP. It was really a theorical password. I dont know if i will do a customized lab for it. But i intend to do the Courseware labs in the Ip services modules. before coninuing the lecture. The next chapter are about Automation and programmability.

I did one of the customized labs. 9 more to do.I hope to do them tomorrow.

## 1/27/2025

Labs 7.2 doesnt work , i cannot ping from the Internet even when grading are coorect. I did all the lab of modules 7. Now there is only left the labs of module Now inthe Boson courseware. Il try to finish the correspnding chapters befre doing them. So i am almost done with the theory phase to concentrate in labs and exams. Enough for today i will watch a movie later.

## 1/28/2025

I am about in pages 1330. I woould like to read 300 or 400 hundred pages tomorrow. I don 't know. Im am in the LAN Architecture parts , the next part is about Automation and Programability . Im almot done with thetheorical part of the exams.

## 1/29/2025

I did not do a lot of readings today , i was busy with something else. I am at pages 1380 about.

## 1/30/2025

For now i read through pages 1524. I hope to finish with the second edition tomorrow it finishes to pages 1700 about , the rest are annexes.
I plan to do some more reading later. I am in the chapter which are about Network Automotaion which are the last chapters , very theorical and boring chapters.
I want to spend the firt 3 weeks of february in doing labs , and exams . So that i could pass the exams before March , i hope.

## 1/31/2025

Pages 1600.

## 2/1/2025

I finished on pages 1802 . I read some of the chapters about how to prepare. So i am almost done with the teory part. I will try to do the rest of the labs in the Boson CourseWare (about 2 ) later.
Tomorrow i will try to watch the Jeremy'is it new videos about Automoation and Ai. So that i will fully focus on Labs / exercices an extra research.
I think the real fun is about to begin. I am planning to pass the exam in the last week of February. So gotta focus.

i finished the BosonCoureware labs , today. They were pretty straightforward , they were not really labs just to read. I have made a tour of The Boson labs they are about a 100.
SO i will try to make at least 5 a day in the next days. Things are gonna be though.I will try to do one or two tonight. Ill go watch the Jeremy's it latest video now.

I watch the videos ad did th first two labs of Boson , they were alo straight forwrd no configuration just Introduction theory.

## 2/2/2025

Today i did 4  Boson labs so far. they were pretty easy for me. I will try to do at least one more later. I will also try t configure the Anki Software on my Iphone so i can
train myself on the Jeremy'it flash card.

## 2/3/2025

I did two labs until now for today. Some of the labs are time consuming so it takes me some time to do them. I will try to do 3 later. I started to try t configure the Ankiflashcards on My Iphone.
I fund one apps i , i will try to add the deck later as i am unfamilliar with the process it can also take me some time.

## 2/4/2025

I did not do anathing today , i was busy at work but hey at least i installed the anki deck to practice.

## 2/5/2025

I did seven labs today and i finishesd with the Networks fundamentals labs on Boson. I'll try to perhap do one more lab later. But i will  concentrate on flahcards on Anki for the rest of the day we will see if i can do one more lab later.
I did one lab in the Network Access modules. I did some flashcard but i am  kinda limmited for the moment , i have to get premium to be fully operational.

## 2/6/2025

I did 4 labs today. I am advancing with the labs , i plan to pay the premium membership on Anki and i will also study the concepts of the CCNA subjects on Wikipedia for better understanding and better preparation.

## 2/7/2025

I did 6 labs today.

## 2/8/2025

I did one lab

## 2/9/2025

I am almost done with the second modules lab only the last lab is left ot be done.

## 2/10/2025

I did for labs today , i lost some pace , but i got other things on my mind right now.

## 2/11/2025

I was lazy today.

## 2/12/2025

I did about seven Boson labs today and some flashcards. I have to buy the premium version of Anki Asap.

## 2/13/2025

I did 5 labs today and the 50 questions of the free Anki version.I am trying to upgrade the Anki.
