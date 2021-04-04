# SONY RM-SC3 RM-SC30 RM-SC31
## IR Remote codes
![SONY RM-SC3 RM-SC30 RM-SC31](https://raw.githubusercontent.com/konradorlinski/sony-RM-SC5-RM-SC50/master/sony_remote.png)
*Source: aliexpress.com*

### Compatible with:
- CMTCP555
- CMTHPX7
- CMTNE5
- LBTZX6
- LBTZX8
- LBTZX9
- MHCGX250
- CMT-NEZ50
- CMT-NE3
- CMT EH 25
- CMT-U1
- CMT-U1BT

### Description
Here is listing of ir codes, read by Arduino with library IRremote and IR receiver VS1838B. To send this codes to your Sony device use for example: ESP8266 with tasmota-ir firmware and any IR LED diode.

Example command for Tasmota for On/Off function:
```IRsend {"Protocol":"SONY","Bits":12,"Data":"0xA81"}```

### List of codes


| Function | Code | Length (Bits) |
| -------- | -------- | -------- |
| Sleep     | 0x61     | 12     |
| On/Off     | 0xA81     | 12     |
| Display     | 0xD21     | 12     |
| Clock/Timer - select     | 0x461     | 12     |
| Clock/Timer - set     | 0xA61    | 12     |
| Tuner Memory     | 0x701    | 12     |
| Play mode/tunning mode     | 0x14B9C    | 20    |
| Repeat/FM mode     | 0xB4B9C    | 20    |
| Tape     | 0xC41   | 12  |
| CD     | 0xA41   | 12  |
| Tuner     | 0xF01   | 12  |
| Function     | 0x4B09   | 15  |
| Skip to the start or previous file/track/chapter | 0xCB9C | 20 |
| Skip to the end or next file/track/chapter | 0x8CB9C | 20 |
| Back (Fast Backwards) | 0xCCB9C | 20 |
| Fast forward | 0x2CB9C | 20 |
| Play |  0x4CB9C | 20 |
| Pause | 0x9CB9C | 20 |
| Stop |  0x1CB9C | 20 |
| Clear | 0xF0B9C | 20 |
| Volume up | 0x481 | 12 |
| Volume down | N/A | N/A |
| Enter | 0x3EB9C | 20 |
| EQ | 0x6309 | 15 |
| Disc skip | 0x7CB9C | 20 |
| Album - | 0x74B9C | 20 |
| Album + | 0xF4B9C | 20 |


