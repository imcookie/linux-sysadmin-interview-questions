1.	Using the OSI model, which layer has the responsibility of making sure that the packet gets where it is supposed to go?
TCP
2.	What is the subnet mask, network address and broadcast address for the following address: 123.65.47.62/22?
subnet 255.255.252.0
3.	What command is used to show all open ports and/or socket connections on a machine?

4.	What is NAT? What is it used for?
NETWORK ADRESS TRANSLATION for map many private ip to one public and vice versa
5.	Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
10.0.0.0/8
6.	What is a packet filter and how does it work?

7.	What is a proxy and how does it work?

8.	What is ARP and what is it used for?
Adress resolution protocol , to map port with network
9.	What is the difference between TCP and UDP?
TCP - 4 model osi, UDP - 3rd, TCP guarantied packet delivering, UDP is not
10.	What command is used to show the route table for a machine?
route -n
11. Explain asynchronous routing?

12.	What is the purpose of a default gateway?
TO send packet with doesnt have destination in a route table
13.	A TCP connection on a network can be uniquely defined by 4 things.  What are those things?
ip,port,mask,mac adress
14.	When a client running a web browser connects to a web server, what is the source port of the connection?
router's ip
15.	What is the destination port of the connection?
ip adress of a web server
16.	What is SMTP?
simple mail transfer protocol
16.	What is an SMTP relay?
This is a mail server wich forwards email to another smtp server, like a proxy server
16.	Give the basic scenario of how a mail message is delivered via SMTP

17.	What function does DNS play on a network?
Преобразует имена веб сайтов в айпи адреса
17.	What is an A record?
ipv4 адресс сервера
17.	What is an NS record?
name server adress
17.	What is an MX record?
mail server adress
17.	What is a PTR record?
обратная запись
17.	What is a DNS forwarder?

17.	What command is used to lookup DNS records?
dig
17.	What is meant by "Reverse Lookup"?

18.	What is LDAP and what is it used for?
служба каталогов под линукс, для управления пользователями и их правами
19.	What is a DN in LDAP?

20.	What is SSH?

21.	What is SSL?

22.	What is IDS?

23.	What is IPS?

24.	What is the difference between IDS and IPS?

25.	What is meant by the term "DOS Attack"?

26.	What is RAID?

27.	What is swap and what is it used for? 

28.	What command will show the available disk space on the Unix/Linux system?

29.	How do you determine the public and prive IP addresses, if applicable, of a Unix/Linux system from the command line?

30.	What Unix/Linux command will alter a file's ownership?

31.	What Unix/Linux command will alter a file's permissions?

32.	What Unix/Linux command will show all processes running on a system?

33.	What Unix/Linux command will show the details of a file(permissions, size, timestamp)?

34.	What Unix/Linux command would you use to list all currently loaded kernel modules?

35.	What command would you use to telnet to port 7777 on a machine with IP address 10.10.10.128?

36.	What Unix/Linux command(s) will show a system's current resource allocations?

37.	What is the Unix/Linux command to remove a directory and its contents?

38.	What is the name and location of the system log on a Unix or Linux system?

39.	What would you do to recover a lost the root password to a Unix/Linux system?

40.	What is the difference between hardlink and symlink?

41.	What happens when you remove the source to a symlink?

42.	What are some of the security risks of symlinks?

43.	Explain a hardlink

44.	Where is a filename stored?

45.	What happens when a hardlink is removed

46.	how do you know when a file is removed

47.	Write a locking function in bash

48.	What is a pre-emptive kernel, what does that mean to you?

49.	What is an atomic operation?

50.	How does a switch get a mac address?

51.	What type of packet to discover a router? 

52.	How does traceroute work?

53.	A careless sysadmin executes the following command: ```chmod 444 chmod``` - what do you do to fix this?
