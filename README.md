# Deskmini310-EFI

This is the EFI of my Hackintosh build, based on [OpenCore](https://github.com/acidanthera/OpenCorePkg) v0.88。

**Important:** Remember to generate your own SMBIOS following [this guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo).

## Setup

This is working fine with my setup:

* macOS Ventura 13.2
* AsRock DeskMini 310
* Intel i7-8700 ES (QNLW)
* SAMSUNG 970 EVO Plus 500 SSD (**Updated firmware**)
* ADATA DDR4 2666 16G * 2
* BCM94360CS2
* ID-COOLING IS40x
* Unbranded 9pin - dual USB2.0 extension

## Tested

* CPU Power Management
* Ethernet
* Wi-Fi
* Bluetooth
* Audio Jack
* All USB ports (including two extended ports on the side panel and the front Type-C port)
* Dual Monitor with HDMI _ DP
* Sleep
* FileVault
* SIP
* FaceTime
* Handoff
* AirDrop

## Known Issues

* Very slow (multi-minute) boot, with 200+ seconds in SSD trim on Monterey and later.
  * See https://github.com/dortania/bugtracker/issues/192 and [https://www.reddit.com/r/hackintosh/comments/sfqhcc/for_those_experiencing_slow_boot_times_under/](https://www.reddit.com/r/hackintosh/comments/sfqhcc/for_those_experiencing_slow_boot_times_under/).
* Under my dual monitor setup (DP + HDMI), the HDMI one is green each time the system boots. Can be fixed by turning the monitor off and on.
* When shutting down, half of my DP monitor turns dark while the other half and the HDMI monitor still display stuffs (purely aesthetic issue).


