＃Lenovo-Yoga3-Pro-1370_-High-Sierra
黑苹果安装存档
电脑BIOS需要回退至a6cn38ww
使用 EFIshell  修改DVMT值 进入EFIshell  后输入指令：setup_var 0x18C 0x3  
显卡驱动方式是 注入 ig-platform-id 0x161e0001   FakeID 0x0161E8086
电源管理是用的 ACPIBatteryManager.kext  +DSDT 打补丁方式驱动
触摸板+触摸屏驱动方式为  使用Kext Utility 修复权限，然后直接把 VoodooI2C.kext、VoodooI2CELAN.kext、VoodooI2CHID.kext、VoodooI2CUPDDEngine.kext 拖到Kext Utility 安装到S/L/E里面
WiFi+蓝牙驱动方式 为使用AW-CE123H-10.13.0-v1.01.pkg这个软件一键设置

