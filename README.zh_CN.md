# 华擎科技 DeskMini 310 黑苹果 OpenCore EFI

![image](ScreenShot/deskmini.png)

### [English](https://github.com/hackintosh-efi/ASRock-DeskMini-310)

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### 可安装系统

- macOS Monterey 12.x 
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### 硬件

- BIOS版本: P4.40  2020-01-17
- 主  板: ASRock H310M-STX/COM
- 处理器: 英特尔 9代 i7-9700
- 核   显: 英特尔超核心显卡630
- 内   存: 挚科 32G（16G*2）DDR4 2666 Mhz
- 固   态: 金胜维 KingSpec NX2280 1TB Windows 11 + MacOS
- 声   卡: 瑞昱 ALC233
- 有   线: 英特尔 L219-V
- 无   线: BCM94360CS2

### BIOS设置

```
Advanced
  |-- CPU Configuration
      |-- CPU C states Support: Enabled
      |-- CFG Lock: Disabled
  |-- Chipset Configuration
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

### 注意事项

 - 安装完成后请使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 生成自己的三码
 - 请使用电源键进行睡眠唤醒

### 系统截图

![image](ScreenShot/Sonoma.jpg)

### 联系我们

- QQ群: 23304408

![image](ScreenShot/QRCode.png)