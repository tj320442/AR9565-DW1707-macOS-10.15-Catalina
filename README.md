介绍

AR9565 Mac驱动 QCNFA335 Atheros AR9565 QCNFA335 DELL DW1707

安装教程

1.首先打开终端,依次输入以下命令: sudo su 输入密码 sudo mount -uw / killall Finder open /system/library/extensions

2.然后不出意外的话,会打开extensions文件夹, 再打开WIFIAR目录下的软件kext Utillty,把AR9565目录下的IO80211Family.kext拖入kext Utillty中

3.最后把AR9565目录下的ATH9KInjector.kext和Lilu.kext粘贴进extensions目录下,重启即可看到无线网卡已经可以正常使用啦
