# 雷神笔记本 G170SG Clover 配置文件
## 目前支持的功能
1. 核显驱动(注入EDIE-无8苹果)
2. 屏蔽独显(whatevergreen)
3. 原声驱动声卡(AppleALC)
4. Intel Wifi+蓝牙驱动(itlwm.kext+AirportItlwm.kext)
5. 原声电源管理(SSDT-LPC.aml)
6. 屏幕亮度保存(SSDT-PNLF.aml)
7. USB注入
8. 睡眠唤醒
9. 电池电量显示(ACPIBatteryManager.kext)
10. 设置中直接切换操作系统

## 存在的瑕疵
1. 偶现睡眠唤醒后WIFI打不开(需重启)，或者蓝牙断开(开关飞行模式即可解决)

## 目前此配置支持的操作系统版本
- `MacOS Catalina`及以下都支持
