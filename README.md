# FUJITSU-U937_opencore

## 驱动情况

- Opencore 0.93，适配Ventura系统，向下兼容。Sonoma未验证。
- 声卡、显卡加速，intel无线都正常。连接显示器的情况下基本完美。

## 制作方法

- SSDTTime制作SSDT补丁。
- Hackintool 制作显卡补丁。
- OCC选择相应的驱动。


## 使用方法

- OCC  选择机型修改SN码。
- 拷贝BOOT、OC到EFI分区。

## 问题

- 在睡眠后恢复自带显示器闪屏黑屏。如果有解决方案，请联系我。 
- 蓝牙没有折腾。
