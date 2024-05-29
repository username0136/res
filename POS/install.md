## Installation

### Notes
- TWRP SKKK works, but not recommended, utilize it at your own risk.
- Firmware is included with the rom.

### Steps
- Download [boot](https://t.me/QuickDump/49) and [vendor_boot](https://t.me/QuickDump/51) images
- Reboot to fastboot mode (Vol Down + Power)
- Flash boot and vendor_boot: `fastboot flash boot boot.img` and `fastboot flash vendor_boot vendor_boot.img`
- Reboot to recovery: `fastboot reboot recovery`
- Go to ADB Sideload and flash fw: `adb sideload fw-file.zip`
- Now again go to adb sideload and flash rom `adb sideload rom-file.zip` (NOTE: if asks to reboot recovery then deny by clicking no)
- Reboot Recovery and Format Data
- [**Optional**] Flash additional resources if you want (eg. Different Kernel)
- Reboot System :)
