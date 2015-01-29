# ADBEx简单说明


----------


## 目录：

- [adb][adb] (活跃)
 - 其中centraldir.c zipfile.c private.h 在[libzipfile][libzipfile]里
 - list.c 找不到，曾经在[libcutils][libcutils]里
- [AdbWinApi][AdbWinApi] (最近一次更新是六年前)
- include
 - [cutils][cutils] (活跃)
 - [mincrypt][mincrypt] (最近一次更新是一年前)
 - [openssl][openssl] (活跃)
 - [zipfile][zipfile] (最近一次更新是六年前)
 - adb_api.h (存在于api文件夹中)
 - common.h usb100.h win32_adb.h (出处不详)
 - zconf.h zlib.h (zlib 1.2.8版本)
- lib
- [AdbWinUsbApi][AdbWinUsbApi](官方最近一次的更新是六年前)

## 功能：

- 将输入参数从GBK编码转换成UNICODE编码
- 参数中加入wait-for-device时,能等待处于Recovery状态的设备

[adb]: https://github.com/android/platform_system_core/tree/master/adb
[libzipfile]: https://github.com/android/platform_system_core/tree/master/libzipfile
[libcutils]: https://github.com/android/platform_system_core/tree/master/libcutils
[AdbWinApi]: https://github.com/android/platform_development/tree/master/host/windows/usb/api
[cutils]: https://github.com/android/platform_system_core/tree/master/include/cutils
[mincrypt]: https://github.com/android/platform_system_core/tree/master/include/mincrypt
[openssl]: https://github.com/android/platform_external_openssl/tree/master/include/openssl
[zipfile]: https://github.com/android/platform_system_core/tree/master/include/zipfile
[AdbWinUsbApi]: https://github.com/android/platform_development/tree/master/host/windows/usb/winusb
