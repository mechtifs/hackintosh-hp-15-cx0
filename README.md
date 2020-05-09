# HP Pavillion Gaming Laptop 15-cx0xxx (aka. 光影精靈四代) Hackintosh Clover EFI
[中文](https://github.com/mechtifs/hackintosh-hp-15-cx0/blob/master/README_zh.md)  
Tested on 15-cx0074tx  
Confirmed working on macOS Catalina 10.15.4
### Confirmed Working
- Intel UHD 630 Graphics Card
- Elan Touchpad
- Realtek ALC295 Speakers
- Web Camera
- Bluetooth
- Headphone Jack
- LAN
- USB
- Android USB Tethering
- Sleeping
### Known Issues
- Nvidia card won't work.
- Wifi (**Experimental**: To make wifi working, please refer to [zxystd/itlwm](https://github.com/zxystd/itlwm/blob/master/.github/README_en.md)).
- Touchpad is buggy, no way to fix that due to the old and closed source driver.
- No sound after sleeping without CodeCommander.kext, which should be fixed by AppleALC.kext.
