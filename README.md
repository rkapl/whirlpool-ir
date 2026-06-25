# Whirpool AC IR Remote for Linux (e.g. Raspberry Pi)

Just a script that encodes and sends commands to Whirpool A/C units such as PACW29COL.
It should work with any linux supported blaster.

Tested on Raspberry Pi with `gpio-ir` and resistor + IR LED. 

`config.txt`
```
dtoverlay=gpio-ir-tx,gpio_pin=2 # for sending commands
```