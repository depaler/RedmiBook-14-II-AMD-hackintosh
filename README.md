# RedmiBook-14-II-AMD-hackintosh

## 请使用 GenSMBIOS 或其他工具 更换SMBIOS
## 安装Macos时请关闭NootedRed
## 跑码时卡顿请耐心等待

## Macos支持
- ✅ macOS Ventura 13.4
- 其他系统自测

## 配置

Type | Spec | 支持性
:---------|:---------|:---------
Model Name | RedmiBook 14 II 锐龙版 | 支持
CPU | AMD Ryzen™ 5 4500U | 支持
RAM | 16 GB 2667 MHz DDR4 | 支持
Wi-Fi | Realtek 8822CE | 不支持
蓝牙 | Realtek 8822CE | 不支持
Audio | Realtek ALC256 | 支持
硬盘 | PM881 | 支持
键盘 | PS2 controller | 支持
触摸板 | ELAN230A |支持
USB | 关闭XCHI | 支持


## 问题

### USB
使用UMAF工具对XCHI控制器进行禁用
https://github.com/DavidS95/Smokeless_UMAF

XCHI控制器 | 接口
:---------|:---------
xchi0 | 左usb3.0 Type-C
xchi1 | 右usb2.0

### 网络
- 更换AX200/201/210 并打上驱动
- 插入 macos可驱动的 有线/无线 网卡
- 使用手机usb网络共享

### 睡眠
### 内置麦克风

## Credits

- [Apple](https://www.apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and most Kexts.
- [NootInc](https://github.com/NootInc) for all the hard work to support AMD iGPU and trackpad.
- [ExtremeXT](https://github.com/ExtremeXT) for the instruction to disable XHC1
- And anyone else that helped to develop and improve hackintoshing.