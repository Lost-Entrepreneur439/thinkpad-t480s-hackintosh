# thinkpad-t480s-hackintosh
 A prebuilt OpenCore EFI for macOS Ventura on the Lenovo ThinkPad T480s

This is a macOS Ventura EFI for the Lenovo ThinkPad T480s, with support for Intel Wi-Fi cards. 13.5 working, with OpenCore 0.9.3 and fully up to date kexts. Remember to keep your kexts and OpenCore up to date! Remember to change your SMBIOS data too.

Follow the "Downloading macOS" section in the Dortania guide to get macOS. ***Support will not be offered if you get macOS from any other source.*** https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos

![Screenshot](https://github.com/Lost-Entrepreneur439/thinkpad-t480s-hackintosh/blob/main/untitled.png)

# Specs of my specific unit:
- CPU: Intel Core i5-8350u
- GPU: Intel UHD Graphics 620
- RAM: 16GB (8GB soldered, 8GB Kingston stick inserted)
- Touchpad: Elan SMBus
- Audio: Realtek ALC257
- Wi-Fi: Intel Wireless-AC 8265
- Ethernet: Intel I219-LM
- SSD: Intel 7600p 256GB

# Set BIOS settings as follows
- Config -> Network -> Wake On LAN -> Disabled
- Config -> Network -> Wake On LAN from Dock -> Disabled
- Config -> CPU -> Intel (R) Hyper-Threading Technology -> Enabled
- Security -> Security Chip -> Security Chip -> Disabled
- Security -> Virtualization -> Intel (R) Virtualization Technology -> Enabled
- Security -> Virtualization -> Intel (R) VT-d Features -> Disabled
- Security -> I/O Port Access -> Thunderbolt(TM) 3 -> Disabled
- Security -> Secure Boot -> Secure Boot -> Disabled
- Security -> Intel(R) SGX -> Intel (R) SGX Control -> Disabled
- Startup -> UEFI/Legacy Boot -> UEFI Only
- Startup -> CSM Support -> No

# Credits
[Acidanthera](https://github.com/acidanthera) -- Made OpenCore, AppleALC, BlueToolFixup, BrightnessKeys, IntelMausi, Lilu, NVMeFix, SMCBatteryManager, SMCProcessor, SMCSuperIO, VirtualSMC, VoodooPS2Controller and WhateverGreen
[OpenIntelWireless](https://github.com/OpenIntelWireless) -- Made Airportitlwm, IntelBluetoothFirmware and IntelBTPatcher
[Avery Black](https://github.com/1Revenger1) -- Made ECEnabler
[FireWolf](https://github.com/0xFireWolf) -- Made GenericCardReaderFriend
[USBToolBox](https://github.com/USBToolBox) -- Made USBToolBox and UTBMap
[VoodooSMBus](https://github.com/VoodooSMBus) -- Made VoodooSMBus
[zhen-zen](https://github.com/zhen-zen) -- Made YogaSMC
[CorpNewt](https://github.com/corpnewt) -- Made SSDTTime, which was used to make SSDTs.
[dortania](https://github.com/dortania) -- Made the OpenCore Install Guide which was used to make this EFI.