# FengMai-S
# 锋麦S黑苹果
# 使用OpenCore0.7.1 OC引导
# 实现的功能：
## 1、 核显驱动
## 2、 声卡：ALC269VC，使用仿冒声卡（ID=7或8）,支持外放及内置麦克风
## 3、 无线网卡：博通BCM4360免驱
## 4、 蓝牙：在驱动中注入 供应商ID：0x0B05 ，产品ID：0x180A 可以驱动，支持隔空投送
## 5、 关机、睡眠正常
## 6、 USB定制
## 7、 DSDT补丁注入IRQ声卡补丁以及Brightness fix	graphics/graphics_PNLF.txt显示器亮度补丁，可以Fn+快捷键调节亮度和声音
# 无法驱动的模块
## GTX960m独立显卡无法驱动
