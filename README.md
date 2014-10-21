ADBEx
=====

增强版ADB  

从[https://github.com/android/platform_system_core/tree/master/adb](https://github.com/android/platform_system_core/tree/master/adb)拉下来的adb，我把代码放到了VS项目里，顺便加了一些功能。

目前功能  

- 将输入参数从GBK编码转换成UNICODE编码
- 参数中加入wait-for-device时,能等待处于Recovery状态的设备
