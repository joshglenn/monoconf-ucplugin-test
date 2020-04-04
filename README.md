# CNC Touch Plugin for UCCNC

## Status of Project

###
Fixed crashing... still not disposing and restarting the server properly when closing the plugin form

### Date: 2020-03-26 
Status: Position server initial implementation complete.
Issues: Does not disconnect without crashing UCCNC

Start up with the plugin enabled, then telnet to the ip address on port 2031.

```
telnet ip.address.of.server 2031
```

 