# cisco-config all update !!


# Start simple config

| Command | 	Purpose |
| --- | --- |
| enable | Logs you into enable mode, which is also known as user exec mode or privileged mode |
| configure terminal | Logs you into configuration mode |
| interface fastethernet/number | Enters interface configuration mode for the specified fast ethernet interface |
| reload | An exec mode command that reboots a Cisco switch or router |
| hostname name | Sets a host name to the current Cisco network device |
| copy from-location to-location | An enable mode command that copies files from one file location to another |
| copy running-config startup-config | An enable mode command that saves the active config, replacing the startup config when a Cisco network device initializes |
| copy startup-config running-config | An enable mode command that merges the startup config with the currently active config in RAM |
|write erase|An enable mode command that deletes the startup config|
|erase startup-config|An enable mode command that deletes the startup config|
|ip address ip-address mask|Assigns an IP address and a subnet mask|
|shutdown|Used in interface configuration mode. “Shutdown” shuts down the interface, while “no shutdown” brings up the interface.|
|no shutdown|Used in interface configuration mode. “Shutdown” shuts down the interface, while “no shutdown” brings up the interface.|
|ip default-gateway ip_address|Sets the default gateway on a Cisco device|
|show running-config|An enable mode command that displays the current configuration|
|description name-string|A config interface command to describe or name an interface|
|show running-config interface interface slot/number|An enable mode command to display the running configuration for a specific interface|
|show ip interface [type number]|	Displays the usability status of interfaces that are configured for IP|
|ip name-server serverip-1 serverip-2|A configure mode command that sets the IP addresses of DNS servers|

# Troubleshooting Commands
| Command | 	Purpose |
| --- | --- |
| ping {hostname// system-address} [source source-address] | Used in enable mode to diagnose basic network connectivity |
|speed {10 // 100 // 1000 // auto}|An interface mode command that manually sets the speed to the specified value or negotiates it automatically|
|duplex {auto // full // half}|An interface mode command that manually sets duplex to half, full or auto|
|cdp run // no cdp run|A configuration mode command that enables or disables Cisco Discovery Protocol (CDP) for the device|
|show mac address-table|Displays the MAC address table|
|show cdp|Shows whether CDP is enabled globally|
|show cdp neighbors[detail]|Lists summary information about each neighbor connected to this device; the “detail” option lists detailed information about each neighbor|
|show interfaces|Displays detailed information about interface status, settings and counters|
|show interface status|Displays the interface line status|
|show interfaces switchport|Displays a large variety of configuration settings and current operational status, including VLAN trunking details.|
|show interfaces trunk|Lists information about the currently operational trunks and the VLANs supported by those trunks|
|show vlan // show vlan brief|Lists each VLAN and all interfaces assigned to that VLAN but does not include trunks|
|show vtp status|Lists the current VTP status, including the current mode|

# Configuring the Time Zone
| Command | 	Purpose |
| --- | --- |
| clock timezone EST -5 0 |  (for example, PST or EST). The offset-hours argument is the offset from the UTC and the range is from –23 to 23 hours. The range for the offset-minutes argument is from 0 to 59 minutes. |







# Interface 

```
show interface status
show interface brife
show interface vlan xxx
show interface port-channel xxx
```

