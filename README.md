# Cisco-Config By Ton

<img src=Cisco-Logo.png/>


- [Start simple config](basic%20simple%20config.md)

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

# Check TCAM CAPA
| Command | 	Purpose |
| --- | --- |
|show hardware capacity | begin TCAM|Displays Capacity Performance|

