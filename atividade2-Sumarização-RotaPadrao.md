### RIP Router - RJ
enable
configure terminal
interface s0/0/0
ip adress 200.200.200.1 255.255.255.252
no shutdown
interface g0/0
ip adress 172.16.10.254 255.255.255.0
no shutdown
interface g0/1
ip adress 172.16.20.254 255.255.255.0
no shutdown
exit
router rip
version 2
network 172.16.0.0
network 200.200.200.0