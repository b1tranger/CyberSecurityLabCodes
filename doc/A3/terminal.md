```
┌──(kali㉿kali)-[~]
└─$ ip addr
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 00:0c:29:34:10:b5 brd ff:ff:ff:ff:ff:ff
    inet 192.168.23.128/24 brd 192.168.23.255 scope global dynamic noprefixroute eth0
       valid_lft 1369sec preferred_lft 1369sec
    inet6 fe80::4639:1d6c:4a47:74d4/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
                                                                             
┌──(kali㉿kali)-[~]
└─$ sudo wireshark
[sudo] password for kali: 
 ** (wireshark:12191) 06:56:29.944726 [GUI WARNING] -- Failed to register with host portal QDBusError("org.freedesktop.portal.Error.Failed", "Could not register app ID: Connection already associated with an application ID")

┌──(kali㉿kali)-[~]
└─$ sudo wireshark
 ** (wireshark:13643) 06:59:07.366043 [GUI WARNING] -- Failed to register with host portal QDBusError("org.freedesktop.portal.Error.Failed", "Could not register app ID: Connection already associated with an application ID")
 ** (wireshark:13643) 06:59:55.221146 [Capture MESSAGE] -- Capture Start ...
 ** (wireshark:13643) 06:59:55.255203 [Capture MESSAGE] -- Capture started
 ** (wireshark:13643) 06:59:55.255225 [Capture MESSAGE] -- File: "/tmp/wireshark_eth0Y4KLV3.pcapng"
 ** (wireshark:13643) 07:58:38.248216 [Capture MESSAGE] -- Capture Stop ...
 ** (wireshark:13643) 07:58:38.297547 [Capture MESSAGE] -- Capture stopped.



```
