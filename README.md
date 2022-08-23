# cisco-config

# enables snmp server

#snmp-server community public ro

#snmp-server community private rw

#snmp-server location [your location]

#snmp-server host x.x.x.x version 2c private

#snmp-server enable traps

# static route with wan [map ip wan]

#ip route x.x.x.x 255.255.255.248 x.x.x.x

# MTU9000  on L2 Switch

#policy-map type network-qos jumbo

#class type network-qos class-default

#mtu 9216



