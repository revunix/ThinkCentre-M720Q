![Model](https://www.hackintosh-forum.de/attachment/168370-lenovo-thinkcentre-m720-tiny-9qgyqmrzvso0xo-png/)


[![buymeacoffee](https://i.imgur.com/iYsbmQO.png)](https://www.buymeacoffee.com/revunix)

## Hardware
Components | Recommended
------------ | -------------
**Motherboard** | ThinkCentre M720 Tiny - Model: 10T700BGGE
**CPU** | Intel i5 9400T - 1,8 GHz
**WiFi** | [BCM94360NG](https://www.aliexpress.com/item/4001120137796.html?)
**Graphics Card** | Intel UHD Graphics 630
RAM | 32GB (2x16GB) CT2K16G4SFD824A DDR4 2400 MHz CL17
macOS | 12.2 (21D48)
OpenCore | v0.7.7 (stable)


## Included items table
Items | Last Version | Comments
------------ | ------------- | -------------
[OpenCore](https://github.com/acidanthera/OpenCorePkg/releases) | 0.7.7 |
[Lilu](https://github.com/acidanthera/Lilu/releases/latest) | 1.6.0 | 
[AppleALC](https://github.com/acidanthera/AppleALC/releases/latest) | 1.6.9 |
[VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases/latest) | 1.2.9 |
[WhateverGreen](https://github.com/acidanthera/whatevergreen/releases/latest) | 1.5.7 |
[RealtekRTL8111](https://github.com/RehabMan/OS-X-Realtek-Network) | 2.4.2 |
USBMap.kext | 1.0 | **[you have to created it!!](https://github.com/corpnewt/USBMap)**

## USB Mapping

[USBMap Repo](https://github.com/corpnewt/USBMap)

    git clone https://github.com/corpnewt/USBMap
    cd USBMap
    chmod +x USBMap.command

If you are done ... copy USBMap.kext into the Kexts folder.

    Kernel > Quirks > XhciPortLimit to NO
    Kernel > Add > 7 > Enabled to YES

## Updates
* 2022-01-23 / Version 1.2
	- Released with OpenCore 0.7.7
	- Updated kexts
	- Fixed USBPort.kext

* 2021-05-04 / Version 1.1 
	- Released with OpenCore 0.6.9
	- Updated kexts
	- Removed VirtualSMC.kext
	- Removed NVMeFix.kext

* 2020-12-12 / Version 1.0
	- Released with OpenCore 0.6.4.
