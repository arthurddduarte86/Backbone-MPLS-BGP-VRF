# Network topology

## Information about the version 2.0

```
Version 2.0
* Created Bastion Server/Jump Server to access routers on MPLS topology
* Configuration for remote access, telnet and ssh, in Backbone MPLS: access only using the Linux Server
* No encryption and more security added due the limitations in Eve-ng
```

###
Linux user and password:  user: eve   //password: eve
Cisco routers in Backbone: user: arthur   //password: arthur

Code used in routers

```
enable
conf t
enable secret arthur
username arthur secret arthur
access-list 10 permit 10.101.101.0 0.0.0.3
line vty 0 5
login local
transport input telnet ssh
access-class 10 in
exit
```



### Routers and devices "Images": 


Cisco
c7200-adventerprisek9-mz.152-4.S7.image
isrv-universalk9.17.03.03<src="https://labhub.eu.org/UNETLAB%20II/addons/qemu/Cisco%20ISRv/isrv-universalk9.17.03.03.tgz">
Linux
Ubuntu Server<src="https://labhub.eu.org/UNETLAB%20I/addons/qemu/linux-ubuntu-18.04-server">



[Topologia] 
<p float="left"><img src=""></p>

[Connectio from Jump-Server to TXCOREBR10#]<img src="">
