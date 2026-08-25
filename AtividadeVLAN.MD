<!-- Switch_Lab1 -->

enable
configure terminal
hostname Switch_Lab1

vlan20
name LAB_10
exit

interface fastEthernet 0/1
switchport mode access
switchport access vlan 10
no shutdown
exit

interface fastEthernet 0/2
switchport mode access
switchport access vlan 10
no shutdown
exit

interface fastEthernet 0/24
switchport mode access
switchport access vlan 10
no shutdown
exit

copy running-config startup-config

<!-- Switch_Lab2 -->

enable
configure terminal
hostname Switch_Lab2

vlan20
name LAB_20
exit

interface fastEthernet 0/1
switchport mode access
switchport access vlan 20
no shutdown
exit

interface fastEthernet 0/2
switchport mode access
switchport access vlan 20
no shutdown
exit

interface fastEthernet 0/24
switchport mode access
switchport access vlan 20
no shutdown
exit

copy running-config startup-config

<!-- Switch_Lab4 -->

enable
configure terminal
hostname Switch_Lab4

vlan20
name LAB_40
exit

interface fastEthernet 0/1
switchport mode access
switchport access vlan 40
no shutdown
exit

interface fastEthernet 0/2
switchport mode access
switchport access vlan 40
no shutdown
exit

interface fastEthernet 0/24
switchport mode access
switchport access vlan 40
no shutdown
exit

copy running-config startup-config

<!-- Switch_Lab5 -->

enable
configure terminal
hostname Switch_Lab5

vlan20
name LAB_50
exit

interface fastEthernet 0/1
switchport mode access
switchport access vlan 50
no shutdown
exit

interface fastEthernet 0/2
switchport mode access
switchport access vlan 50
no shutdown
exit

interface fastEthernet 0/24
switchport mode access
switchport access vlan 50
no shutdown
exit

copy running-config startup-config

<!-- Roteador -->

enable
configure terminal
hostname Roteador

interface fastEthernet 0/0
no shutdown
exit