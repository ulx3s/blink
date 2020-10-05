# Blink ULX3S LED

## Connecting ULX3S

You need to connect to USB1 (US1) connector to the host computer in order to program the board.

<img src="https://raw.githubusercontent.com/ulx3s/quick-start/master/images/ulx3s-usb1.jpg?raw=true" width="400">

## Download programmer

Download fujprog for your OS [latest version of fujprog](https://github.com/kost/fujprog/releases).

Extract fujprog to "any-folder" on your drive

```
MacOS: export PATH=[path-to-fujprog]:$PATH
Linux: export PATH=[path-to-fujprog]:$PATH
Windows Powershell: $ENV:PATH = "[path-to-fujprog];" + $ENV:PATH
Windows cmd.exe: PATH=[path-to-fujprog];%PATH%
```

## Uploading

Upload blik led for your board version

```
git clone https://github.com/ulx3s/blink.git
cd blink
fujprog blink_85f.bit
```

On linux you may need to add udev rule

https://github.com/emard/ulx3s/blob/master/doc/MANUAL.md#programming-over-usb-port-us1

## Next step

Build your own blink LED [QuickStart](https://github.com/ulx3s/quick-start).
