### Instructions
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

* Notes: If you find the DW1820A not working properly you may try the pin-masking trick. Same pins should be masked for any computer. The following picture shows the pins-to-mask in red color.
This pin-masking picture/method by: [Juan-VC](https://github.com/Juan-VC)

![Imgur](https://i.imgur.com/kof6tzz.png)
		

