Python PELCO-D implementation API

Purpose:
PELCO-D Motor Control over UDP or RS-485

### Dependencies:
- Python
- Pip
- pyserial module

### Instructions to install on Ubuntu 18.04
1. Install python `sudo apt install python`
2. Install pip `sudo apt install python-pip`
3. Install pyserial `pip install pyserial`

### Use
```import libpelco as lib

cctv = lib.PELCO_Functions

cctv.pantilt_left_pressed("20") #moves left
cctv.pantilt_stop() #stops
```

Inspired by https://github.com/weqaar/libpelco
