HSRP (First-Hop Redundancy Protocol)

TOPOLOGY:
------------------------------------
2 routers (R1 and R2)

1 switch (S1)

2 PCs in VLAN 10

Both routers share one virtual IP for default gateway.

IP Addressing Plan:
------------------------------------
VLAN 10 LAN:

Network: 192.168.10.0/24

HSRP Virtual IP: 192.168.10.1

R1 (Active router) 

g0/0 = 192.168.10.2/24

R2 (Standby router) 

g0/0 = 192.168.10.3/24

PCs:

Gateway = 192.168.10.1 (the HSRP virtual IP)
