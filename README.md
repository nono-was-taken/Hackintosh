# Hackintosh Backup Files

## Disclaimer

You cannot use this EFI as it is. 

It's mainly for my personal Backup. Check out [Dortania‘s guide](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) for more Information about Hackintosh.


## General Information

- Guide Used: [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)
- [Open Core: 0.6.3 `f152c95`](https://github.com/acidanthera/OpenCorePkg)
- macOS 11.0.1 `20B29` 
- SMBIOS: iMac19,1
- [Sanity Check](https://opencore.slowgeek.com/?file=coffeelake063EVQoPi&rs=coffeelake063)

## Hardware

- CPU: Intel i7-9700K
- GPU: iGPU UHD 630
- Motherboard: MSI Z390 Gaming Edge AC
- RAM: 2x 8GB Corsair Dominator Platinum RGB 3600Mhz 16-18-18-36
- Audio Codec: Realtek ALC1220P Codec
- Ethernet Card: Intel I219-V Gigabit LAN controller
- Wifi & Bluetooth: Intel Wireless-AC 9462 Card (the build-in Adapter from the Motherboard)
- Power Supply: Corsair RM750i 750W
- Storage:
    + Samsung SSD 850 EVO 250GB (Hackintosh Drive)
    + Samsung SSD 970 EVO 1TB (Windows Drive)
    + Corsair Force GT (Data Drive)


## [Kexts used](./EFI/OC/Kexts/)

- AirportItlwm.kext
- AppleALC.kext
- IntelBluetoothFirmware.kext
- IntelBluetoothInjector.kext
- IntelMausi.kext
- Lilu.kext
- NVMeFix.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBPorts.kext
- VirtualSMC.kext
- WhateverGreen.kext

