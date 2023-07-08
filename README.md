# FUJITSU-U937_opencore

- FUJITSU-U937，号称最轻的14存笔记本，单机不超过800g。
- i5-7300U，intel G620核显。intel AC 8265无线。 
- 2133DDR4内存（我又加了一根16G 2644ddr4）。


## 驱动情况

- Opencore 0.93，适配Ventura系统，向下兼容。Sonoma未验证。
- 声卡、显卡加速，intel无线都正常。连接显示器的情况下基本完美。

## 制作方法

- SSDTTime制作SSDT补丁。
- Hackintool 制作显卡补丁。
- OCC选择相应的驱动。
- 抄的其他oc的配置文件。


## 使用方法

- OCC  选择机型修改SN码。
- 拷贝BOOT、OC到EFI分区。

## 问题

- 在睡眠后恢复自带显示器闪屏黑屏。用Hackintool搞了好久，重启了100多次没搞定。如果有解决方案，请联系我。 
- 蓝牙没有折腾。
