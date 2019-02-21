[👉 README IN English](#pi_bakup)
# 树莓派备份脚本
一个帮助我们备份树莓派系统的小脚本
### 测试

2019-02-21 Debain9 Stretch 备份至 NTFS u盘 通过

如果你在使用脚本中成功备份或者失败，请在issues中提出来，方便改进，谢谢


### 使用方法
```sh
git clone https://github.com/cuifeiran/pi_bakup.git 

cd pi_bakup

sh bak.sh 

```

然后请选择备份情况，1：从SD卡备份到u盘（默认为第一个u盘:/dev/sda1）2:从u盘启动的备份到另一张u盘（默认为第二个u盘:/dev/sda2）

*其他需求请自行修改代码*

**备份过程一般需要20分钟以上，执行到part1时不会显示进度，请耐心等待。**

### 改动
2019-02-21 改动：创建的映像大小从1.3


### 参考： 
>[conanwhf/RaspberryPi-script](https://github.com/cuifeiran/RaspberryPi-script/blob/master/rpi-backup.sh)

 - 感谢前辈付出！(没有forked的原因是这个脚本可能被我改糟，不想污染master所以新建了一个仓。)


***
# pi_bakup
help us to backup our piSD or piUSB to UsbSrotage

### TEST
If you have any trouble with backup success or failure, please submit result in Issues to help me improve script. Thanks.

2019-02-21 Debain9 Stretch backup to NTFS usb storage pass

### HOW TO USE IT

```sh
git clone https://github.com/cuifeiran/pi_bakup.git 
cp pi_bakup
sh bak.sh 
```

And then,choose1：backup piSD>first USB storage（Default :/dev/sda1）. if your pi system in USB storage,choose2:backup piUSB >second USB storage（Default:/dev/sda2）

*other demand please revise the code by yourself*

**The backup process usually takes more than 20 minutes. The progress will not be displayed when the backup process is executed to part1. Please wait patiently.**

### UPDATE
2019-02-21 change：create img size 1.3 multiple to 1.5 multiple


### REFERENCE RESOURCES： 
>[conanwhf/RaspberryPi-script](https://github.com/cuifeiran/RaspberryPi-script/blob/master/rpi-backup.sh)

  - Thank your predecessors for giving! (The reason why there is no forked is that the script may have been worsened by me. I didn't want to pollute the master, so I built a new warehouse. )
