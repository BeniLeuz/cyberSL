# Advanced infos

## Host infos
ip: 192.168.64.8

### Nmap
Starting Nmap 7.95 ( https://nmap.org ) at 2025-10-14 18:07 EDT
Nmap scan report for 192.168.64.8
Host is up (0.0038s latency).
Not shown: 995 closed tcp ports (reset)
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7.6p1 Ubuntu 4ubuntu0.3 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   2048 8c:9f:7e:78:82:ef:76:f6:26:23:c9:52:6d:aa:fe:d0 (RSA)
|   256 2a:e2:f6:d2:52:1c:c1:d0:3d:aa:40:e6:b5:08:1d:45 (ECDSA)
|_  256 fa:c9:eb:58:e3:d2:b7:4a:74:77:fc:69:0e:b6:68:08 (ED25519)
80/tcp   open  http    nginx 1.14.0 (Ubuntu)
|_http-server-header: nginx/1.14.0 (Ubuntu)
|_http-title: W3.CSS Template
5000/tcp open  http    nginx 1.14.0 (Ubuntu)
|_http-generator: WordPress 5.7.2
|_http-server-header: nginx/1.14.0 (Ubuntu)
|_http-title: fsociety &#8211; Just another WordPress site
8081/tcp open  http    nginx 1.14.0 (Ubuntu)
|_http-title: Home
|_http-server-header: nginx/1.14.0 (Ubuntu)
|_http-generator: Joomla! - Open Source Content Management
| http-robots.txt: 15 disallowed entries 
| /joomla/administrator/ /administrator/ /bin/ /cache/ 
| /cli/ /components/ /includes/ /installation/ /language/ 
|_/layouts/ /libraries/ /logs/ /modules/ /plugins/ /tmp/
9001/tcp open  http    nginx 1.14.0 (Ubuntu)
|_http-generator: Drupal 7 (http://drupal.org)
|_http-server-header: nginx/1.14.0 (Ubuntu)
|_http-title: fsociety.web
MAC Address: 9E:94:B7:EB:CC:3D (Unknown)
Device type: general purpose|router
Running: Linux 4.X|5.X, MikroTik RouterOS 7.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5 cpe:/o:mikrotik:routeros:7 cpe:/o:lin
ux:linux_kernel:5.6.3
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4), MikroTik RouterOS 7.2 - 7.5 (Linux 5.6.3)
Network Distance: 1 hop
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

TRACEROUTE
HOP RTT     ADDRESS
1   3.78 ms 192.168.64.8

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 20.77 seconds



### URLS:
wordpress: http://fsociety.web:5000/admin
joomla: http://fsociety.web:8081/administrator
