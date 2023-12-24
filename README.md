# ASRock DeskMini 310 Hackintosh OpenCore EFI

![image](ScreenShot/deskmini.png)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### Hardware

- BIOS Version: P4.40  2020-01-17
- Motherboard: ASRock H310M-STX/COM
- CPU: Intel 9th i7-9700
- iGPU: Intel UHD 630
- Memo: ZHIKE 32G（16G*2）DDR4 2666 Mhz
- SSD: KingSpec NX2280 1TB Windows 11 + MacOS
- HDA: Realtek ALC233
- LAN: Intel L219-V
- WiFI: BCM94360CS2

### BIOS

```

Advanced
  |-- CPU Configuration
      |-- CPU C states Support: Enabled
      |-- CFG Lock: Disabled
  |-- Chipset Configuration
      |-- Above 4G Decoding: Enabled
      |-- VT-D: Enabled
      |-- Onboard HD Audio: Enabled
  |-- Super IO Configuration
      |-- Serial Port: Disabled
  |-- USB Configuration
      |-- XHCI Hand-off: Enabled 

Security
  |-- Secure Boot: Disabled 
  |-- Intel Platform Trust Technology:: Enabled 

Boot 
  |-- Full Screen Logo: Disabled
  |-- CSM: Disabled
```

### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your SMBIOS
 - Use the Power button to wake up from sleep
 - Automatic switching is not supported after inserting 3.5mm headphones. Please manually select the headphone device in the sound settings
 - Connecting 3.5mm earphones and independent microphones simultaneously can cause a burst sound after waking up from sleep. Please unplug the device and reinsert it

### ScreenShot

![image](ScreenShot/Sonoma.jpg)



### Special Thanks

PCBETA ：[Coldsparkle](https://i.pcbeta.com/space-uid-4597992.html)  &  GITHUB ：[viorel78](https://github.com/viorel78)  It's the same person

He customized the sound card [Layout ID 18](https://github.com/acidanthera/AppleALC/pull/668)  with DeskMini H310  ALC235  

Thank you for your customization ！

### Contact Us 

- QQ Group: 23304408

![image](ScreenShot/QRCode.png)