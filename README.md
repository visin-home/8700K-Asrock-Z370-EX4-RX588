# Shinelon-N650DU-QN8J-macOS(OpenCore)

This repository provides OpenCore configuration files for Shinelon-N650DU-QN8J. 

[![release](https://img.shields.io/badge/下载-release-blue.svg)](https://github.com/visin-home/Shinelon-N650DU/releases) 


## 电脑配置

| 规格     | 详细信息 |
| -------- | ---------------------------------------- |
| 电脑型号 | Shinelon-N650DU |
| 处理器 | Intel i7 8700T ES(QN8J)|
| 内存插槽一 | Team Group  DDR4 2666MHz 16G|
| 内存插槽二 | Team Group  DDR4 2666MHz 16G |
| NvMe | 海康威视 C2000 PRO 512G |
| 集成显卡 | Intel UHD Graphics 630  |
| 显示器   | 内建显示器 15.6 - 英寸 (1920 x 1080) |
| 声卡     | Realtek ALC269  |
| 网卡     | Realtek RTL8111|
| Wifi&蓝牙     |  BCM94360CD|

## 详情
    之前用的是 Clover 引导,但太臃肿了,不好维护,再加上很多驱动已经不对 Clover 进行测试了,所以转为了 OpenCore 进行引导.
    这个引导主要是 @Tian羽 完成的,我只是稍微做了下修改.    
原贴地址:[http://bbs.pcbeta.com/viewthread-1833314-1-1.html](http://bbs.pcbeta.com/viewthread-1833314-1-1.html).

感谢 @Tian羽 的辛勤付出.
		再他的基础上,我做了如下工作:

1. 添加 CPUFriend.kext,低频 800MHz.
2. GPU 帧缓冲修复.
3. Duang 一声开机声音.
4. 开机引导菜单图形化(默认是隐藏直接进入 macOS 的,需要开机的时候连续按 ESC 或 ALT 键呼出引导菜单).
### 工作:
1. 变频 OK.
2. 睡眠 OK.
3. 唤醒 OK.
4. 声卡 OK.
5. 触控 OK.
6. 声卡 OK.
7. 亮度可调 OK.
8. HDMI&音频 OK.
### 不工作&不完善:

1. SD 卡,应该能驱动,但速度很慢,没搞它,也用不到.
2. 键盘按键基本是适配的,但亮度调节快捷键不行,暂时的解决办法是插入一个外接键盘,然后指定调节亮度的按键.
3. 外接显示器的话,需要开机进入桌面以后再插入 HDMI 外接显示器.
