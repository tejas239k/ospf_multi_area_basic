# ospf_multi_area_basic
Multi Area configuration for OSPF with area 0 as a backbone area connected with another area i.e area 10 . The important command to be considered here is the configuring router ospf 1(Process Id) and after that command the network command i.e network 10.0.0.0 0.255.255.255 area 10 Here 0.255.255.255 is the wildcard mask for more check the doc file.
