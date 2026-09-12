```

┌──(kali㉿kali)-[~]
└─$ ping -c 4 8.8.8.8        
PING 8.8.8.8 (8.8.8.8) 56(84) bytes of data.
64 bytes from 8.8.8.8: icmp_seq=1 ttl=128 time=52.8 ms
64 bytes from 8.8.8.8: icmp_seq=2 ttl=128 time=50.1 ms
64 bytes from 8.8.8.8: icmp_seq=3 ttl=128 time=50.1 ms
64 bytes from 8.8.8.8: icmp_seq=4 ttl=128 time=49.9 ms

--- 8.8.8.8 ping statistics ---
4 packets transmitted, 4 received, 0% packet loss, time 3057ms
rtt min/avg/max/mdev = 49.939/50.765/52.843/1.202 ms
                                                                             
┌──(kali㉿kali)-[~]
└─$ nslookup example.com        
Server:         192.168.23.2
Address:        192.168.23.2#53

Non-authoritative answer:
Name:   example.com
Address: 104.20.23.154
Name:   example.com
Address: 172.66.147.243
Name:   example.com
Address: 2606:4700:10::ac42:93f3
Name:   example.com
Address: 2606:4700:10::6814:179a

                                                                             
┌──(kali㉿kali)-[~]
└─$ 

```
