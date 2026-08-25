                                                                             
┌──(kali㉿kali)-[~]
└─$ nmap scanme.nmap.org
Starting Nmap 7.99 ( https://nmap.org ) at 2026-08-24 23:34 -0400
Stats: 0:00:05 elapsed; 0 hosts completed (1 up), 1 undergoing SYN Stealth Scan
SYN Stealth Scan Timing: About 11.50% done; ETC: 23:35 (0:00:38 remaining)
Nmap scan report for scanme.nmap.org (45.33.32.156)
Host is up (0.024s latency).
Other addresses for scanme.nmap.org (not scanned): 2600:3c01::f03c:91ff:fe18:bb2f
Not shown: 996 filtered tcp ports (no-response)
PORT      STATE SERVICE
22/tcp    open  ssh
80/tcp    open  http
9929/tcp  open  nping-echo
31337/tcp open  Elite

Nmap done: 1 IP address (1 host up) scanned in 77.61 seconds

<!-- 
DUMMY IP: 45.33.32.156

from:

Nmap scan report for scanme.nmap.org (45.33.32.156) 

-->

┌──(kali㉿kali)-[~]
└─$ nmap 45.33.32.156   
Starting Nmap 7.99 ( https://nmap.org ) at 2026-08-25 00:00 -0400
Nmap scan report for scanme.nmap.org (45.33.32.156)
Host is up (0.018s latency).
Not shown: 952 filtered tcp ports (no-response), 44 closed tcp ports (reset)
PORT      STATE SERVICE
22/tcp    open  ssh
80/tcp    open  http
9929/tcp  open  nping-echo
31337/tcp open  Elite

Nmap done: 1 IP address (1 host up) scanned in 56.23 seconds

┌──(kali㉿kali)-[~]
└─$ nmap -p 22,80 IP     
Starting Nmap 7.99 ( https://nmap.org ) at 2026-08-25 00:10 -0400
Failed to resolve "IP".
WARNING: No targets were specified, so 0 hosts scanned.
Nmap done: 0 IP addresses (0 hosts up) scanned in 16.02 seconds

                                                             





