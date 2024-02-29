## Installation

### Notes
- OFOX A14 by Pranav is supported
- Do flash global fw for better reliablity, regional fw is fine as well
- Firmware: [Recommended](https://xiaomifirmwareupdater.com/firmware/munch/stable/V14.0.6.0.TLMMIXM/) | [Experimental](https://t.me/QuickDump/23) with "mi" boot logo
- [Debloater](https://t.me/QuickDump/25): use at own risk, and only when you know what you are doing!

### Steps
- Download [boot](https://t.me/QuickDump/12) and [vendor_boot](https://t.me/QuickDump/13) images
- Reboot to fastboot mode (Vol Down + Power)
- Flash boot and vendor_boot: `fastboot flash boot boot.img` and `fastboot flash vendor_boot vendor_boot.img`
- Reboot to recovery: `fastboot reboot recovery`
- Go to ADB Sideload and flash fw: `adb sideload fw-file.zip`
- Now again go to adb sideload and flash rom `adb sideload rom-file.zip` (NOTE: if asks to reboot recovery then deny by clicking no)
- Reboot Recovery and Format Data
- [**Optional**] Flash additional resources if you want (Debloater, Different Kernel)
- Reboot System :)
