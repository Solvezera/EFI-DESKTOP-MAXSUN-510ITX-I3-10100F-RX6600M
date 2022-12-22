# Maxsun H510 ITX + i3 10100F + RX 6600 M + Wifi / BT Fenvi BCM943602CS

![about-13 1](inserir imagem)

**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.7

## Complete hardware specs
| Hardware | Model |
| --- | --- |
| Motherboard | Maxsun H510 ITX @ BIOS E1.4G |
| CPU | Intel i3 10100F @ Stock (All cores (P+E+HT) activated) |
| GPU | RX 6600 M - JIESHUO |
| Memory | 2x 8Gb DDR4 2400Mhz KLISRRE |
| Wifi | Fenvi BCM943602CS - Work OOB |

## What works
- macOS Ventura, macOS Big Sur, macOS Catalina and macOS Monterey
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports are mapped
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't works
- At the moment, everything is working fine.

## Kexts used
- [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases)
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
- [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases)
- [SMCSuperIO.kext](https://github.com/acidanthera/VirtualSMC/releases)
- [SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC/releases)
- [USBMap.kext](https://github.com/corpnewt/USBMap) 
- [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC/releases)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)

## Geekbench Results
- reserved to tests

## Special Notes
- Remember to use GenSMBIOS and change MASKED properties in `config.plist`.

## Special Resources
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- [SSDTTime](https://github.com/corpnewt/SSDTTime)
- [MontEFI](https://github.com/corpnewt/MountEFI)
- [Python 3.9.9](https://www.python.org/downloads/release/python-399)
- [Rename USB](https://dortania.github.io/OpenCore-Post-Install/usb/system-preparation.html)
- [USBMap](https://github.com/corpnewt/USBMap)
- [Hackintool](https://github.com/benbaker76/Hackintool)
- [MaciASL (ACPI)](https://github.com/acidanthera/MaciASL)

## Thanks / Credits
- [Gabriel Luchina - Github](https://github.com/luchina-gabriel)
- [Universo Hackintosh - Youtube](https://www.youtube.com/@UniversoHackintosh)
- [Followed this youtube guide from Gabriel Luchina](https://www.youtube.com/watch?v=5FVxZDXr98o&t=15218s&ab_channel=GabrielLuchina-UniversoHackintosh)
- [BASE EFI - for 10th Intel Gen - Comet Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE)
- [Opencore Team](https://dortania.github.io/getting-started/)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
