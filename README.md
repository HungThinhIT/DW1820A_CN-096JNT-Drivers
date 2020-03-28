# DELL-DW1820A-CN-096JNT-Drivers

This repository contains drivers for DW1820A - CN-096JNT m.2 2230 Wifi card for Mac/Windows/Linux.

### Download
[Download for Mac/Windows/Linux](https://github.com/HungThinh0710/DW1820A_CN-096JNT-Drivers/releases)
   
## MacOS
Information:
- Fixed freezing issues & panic.
- Wifi: Working
- Bluetooth: Working
- Airdrop/Handoff: Working

For 10.12.x => 10.14.x
Install these kext into Clover/kext/Other

```
AirportBrcmFixup.kext
BrcmBluetoothInjector.kext
BrcmFirmwareData.kext
BrcmPatchRAM2.kext
```
For 10.15.x
```
AirportBrcmFixup.kext 
BrcmBluetoothInjector.kext
BrcmFirmwareData.kext
BrcmPatchRAM3.kext
```

## Windows 
This drivers work successfully on Windows 10.

Information:
- WIFI card: DW1820A - CN-096JNT
- Windows: Windows 10 1903 64bit.
- Bluescreen issue: Fixed

Installation method 1 for both wifi and bluetooth.
- Run two exe file (If it's not working, use method 2)

Installation method 2 for both wifi and bluetooth.
- Open devices manager
- Select wifi devices (Maybe "Network controller") / Bluetooth devices
- Right click and select "Update driver software"
- Select "Browse my computer for driver software"
- Navigate to extracted folder of wifi/bluetooth driver
- Next. And it's working.

## Linux
Go to linux folder.

## Credits
* the-darkvoid: Original BrcmPatchRAM idea
* RehabMan: Improvements to kexts
* acidanthera: Further improvements of bluetooth kexts, introduction of BrcmPatchRAM3 and AirportBrcmFixup
