# RedmiBook-14-II-AMD-hackintosh

## 请使用 GenSMBIOS 或其他工具 更换SMBIOS

## 配置

Type | Spec | 支持
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
- 插入 macos 免驱/可打驱动 的 有线/无线 网卡
- 使用手机usb网络共享


