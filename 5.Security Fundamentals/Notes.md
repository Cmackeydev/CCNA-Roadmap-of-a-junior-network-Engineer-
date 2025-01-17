# 5.Security Fundamentals

## 5.6 ACL

Today i did a lab with ACL. I used a basic topology with 3 routers that i used Ospf to advertie the route in the Network. THe topology can be found in `Topology/ACL_lab_1.png`.I configured Standard numbered and Standard named ACL. After checking everything i deleted them and configured extended numberered and extended named ACL. I was really proud of myself when everything worked. I peronnally prefere extended named ACL. Note always remember there is an implicite deny at the end of each ACL , which can sometimes prevent basic protocols so sometimes an implicit permit all can be necessary.