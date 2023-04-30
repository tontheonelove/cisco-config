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







# Interface 

```
show interface status
show interface brife
show interface vlan xxx
show interface port-channel xxx
```

