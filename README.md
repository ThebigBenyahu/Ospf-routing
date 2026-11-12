# Ospf-routing

R1
router ospf 1
router-id 1.1.1.1
network 192.168.1.0 0.0.0.255 area 0
network 10.0.0.0 0.0.0.3 area 0
end
write memory

R2

router ospf 1
router-id 2.2.2.2
network 192.168.2.0 0.0.0.255 area 0
network 10.0.0.0 0.0.0.3 area 0
end
write memory
