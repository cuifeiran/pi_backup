[English](#pi_bakup)
# 树莓派备份脚本
一个帮助我们备份树莓派系统的小脚本
### 使用方法

'''
   git clone https://github.com/cuifeiran/pi_bakup.git 
   cp pi_bakup
   sh bak.sh 
'''

然后请选择备份情况，1：从SD卡备份到u盘（默认为第一个u盘:/dev/sda1）2:从u盘启动的备份到另一张u盘（默认为第二个u盘:/dev/sda2）
** 备份过程一般需要20分钟以上，执行到part1时不会显示进度，请耐心等待。 **

### 改动
2019-02-21 改动：创建的映像大小从1.3


> 参考： [conanwhf/RaspberryPi-script](https://github.com/cuifeiran/RaspberryPi-script/blob/master/rpi-backup.sh)

感谢前辈付出！

没有forked的原因是这个脚本可能被我改糟，所以新建了一个仓。


***
# pi_bakup
help us to backup our piSD or piUSB to UsbSrotage

