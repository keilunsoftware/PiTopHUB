# PiTopHUB
PiTop addon board with Arduino ATMEGA328P programming and breakout

Features:

- USB Hub with 2 free ports and WDPi usb (WDPi can be installed on top of PiTop power hub)
- Full Arduino compatible breakout board (programmable from RPi)
- PiTop 16-18V power connector
- Full RPi GPIO connector (removed permanent 3v3 pin to avoid battery drain, even when off)

Known issues:

- With permanent USB devices connected to RPi USB PiTop experiences a battery drain even when powered off. Need to add an additional switch on the RPi USB power cable

