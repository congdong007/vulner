nmap -p- --min-rate 10  192.168.244.128                                                                                                          
Starting Nmap 7.92 ( https://nmap.org ) at 2022-05-04 09:47 EDT
Nmap scan report for 192.168.244.128 (192.168.244.128)
Host is up (0.0023s latency).
Not shown: 65505 closed tcp ports (reset)
PORT      STATE SERVICE
21/tcp    open  ftp
22/tcp    open  ssh
23/tcp    open  telnet
25/tcp    open  smtp
53/tcp    open  domain
80/tcp    open  http
111/tcp   open  rpcbind
139/tcp   open  netbios-ssn
445/tcp   open  microsoft-ds
512/tcp   open  exec
513/tcp   open  login
514/tcp   open  shell
1099/tcp  open  rmiregistry
1524/tcp  open  ingreslock
2049/tcp  open  nfs
2121/tcp  open  ccproxy-ftp
3306/tcp  open  mysql
3632/tcp  open  distccd
5432/tcp  open  postgresql
5900/tcp  open  vnc
6000/tcp  open  X11
6667/tcp  open  irc
6697/tcp  open  ircs-u
8009/tcp  open  ajp13
8180/tcp  open  unknown
8787/tcp  open  msgsrvr
33354/tcp open  unknown
43246/tcp open  unknown
52389/tcp open  unknown
59667/tcp open  unknown
MAC Address: 00:0C:29:D5:0C:8B (VMware)

Nmap done: 1 IP address (1 host up) scanned in 6.18 seconds