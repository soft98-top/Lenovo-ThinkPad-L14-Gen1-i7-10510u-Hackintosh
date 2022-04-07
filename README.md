# Lenovo-ThinkPad-L14-Gen1-i7-10510u-Hackintosh
EFI of Lenovo-ThinkPad-L14-Gen1-i7-10510u

The EFI of ThinkPad-L14-Gen1

CPU: i7-10510u

Network Card：BCM94352Z

## 2022-04-07

使用[itlwm](https://github.com/OpenIntelWireless/itlwm)解决无线网卡驱动问题，现在可以用WiFi了。

当前使用的驱动支持Monterey，对于**非Monterey**系统，需要到[itlwm](https://github.com/OpenIntelWireless/itlwm/releases)下载对应系统的驱动，然后替换`AirportItlwm.kext`。

## 2022-01-31

解决无法收到最新系统更新的问题（使用RestrictEvents.kext）

## 2022-01-30

更新opencore -> 7.7

## 2021-11-15

更新引导，可升级至macOS 12；

更换alcid，可开启环境音降低功能；

推荐使用 **QTOpenCoreConfig**

[ic005k/QtOpenCoreConfig: OpenCore Auxiliary Tools OpenCore Configurator OCAT (github.com)](https://github.com/ic005k/QtOpenCoreConfig)
