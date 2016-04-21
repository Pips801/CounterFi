# MAC changing
`ip link set wlan0 address 00:00:00:00:00:00`

# Hostname chainging
`setprop net.hostname <hostname>`

# Saved networks

do not autojoin the network
```
network{
  disabled=1
}
```

do not beacon out network
```
network{
  scan_ssid=0
}
```
