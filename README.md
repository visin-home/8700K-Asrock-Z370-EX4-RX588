# 8700K-Asrock-Z370EX4-RX588(OpenCore)

This repository provides OpenCore configuration files for Shinelon-N650DU-QN8J. 

[![release](https://img.shields.io/badge/下载-release-blue.svg)](https://github.com/visin-home/8700K-Asrock-Z370-EX4-RX588/releases) 


## 电脑配置

| 规格     | 详细信息 |
| -------- | ---------------------------------------- |
| 电脑型号 | Asrock Z370EX4 |
| 处理器 | Intel i7 8700k ES(QN8G)|
| 内存插槽一 | 芝奇  DDR4 3200MHz 8G|
| 内存插槽二 | 芝奇  DDR4 3200MHz 8G |
| NvMe | 三星 sm961 512G |
| 集成显卡 | Intel UHD Graphics 630  |
| 独立显卡 | AMD RX580 8G  |
| 声卡     | Realtek ALC1220  |
| 网卡     | Intel I219V2|
| Wifi&蓝牙     |  BCM94360CD|

## 详情
    之前用的是 Clover 引导,但太臃肿了,不好维护,再加上很多驱动已经不对 Clover 进行测试了,所以转为了 OpenCore 进行引导.
    

1. 添加 CPUFriend.kext,低频 800MHz.
2. 添加 RX580 相关参数,ROM修正版：113-C9440C-171;VBIOS版本：113-4E353BU-O4E;EFI驱动程序版本：01.00.3180.
3. Duang 一声开机声音.
4. 开机引导菜单图形化.
### 工作:
1. 变频 OK.
2. 睡眠 OK.
3. 唤醒 OK.
4. 声卡 OK.
5. 声卡 OK.
6. HDMI&音频 OK.
7.硬解 OK.
 
### 不工作&不完善:

