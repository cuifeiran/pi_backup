[👉 README IN English](#RASPBERRY_BACKUP)
# 树莓派备份脚本
一个帮助我们备份树莓派系统的小脚本，适配Ubuntu/Debian https://github.com/cuifeiran/pi_backup
### 测试

- 2019-02-21 Debian9 Stretch 备份至 NTFS u盘 通过

如果你在使用脚本中成功备份或者失败，请在issues中提出来，方便改进，谢谢


### 使用方法
```sh
git clone https://github.com/cuifeiran/pi_bakup.git 

cd pi_bakup

sh bak.sh 

```

然后请选择备份情况，1：从SD卡备份到u盘（默认为第一个u盘:/dev/sda1）2:从u盘启动的备份到另一张u盘（默认为第二个u盘:/dev/sda2）

*其他需求请自行修改代码*

### 注意

由于备份时间过长，若使用SSH，其默认超时配置项可能导致备份中断，建议修改ssh默认超时时间或者安装screen，参考：[崔斐然的CSDN](https://blog.csdn.net/qq_33273956/article/details/87618350)

备份过程一般需要20分钟以上，~~执行到part1时不会显示进度，请耐心等待。~~

### 改动
2019-02-21 改动：新增part1创建映像显示进度

2019-02-21 改动：创建的映像大小从1.3


### 参考： 
>[conanwhf/RaspberryPi-script](https://github.com/conanwhf/RaspberryPi-script)

 - 感谢前辈付出！(没有forked的原因是这个脚本可能被我改糟，不想污染master所以新建了一个仓。)


***
# RASPBERRY_BACKUP
help us to backup our piSD or piUSB to UsbSrotage  Adaptation Ubuntu/Debian https://github.com/cuifeiran/pi_backup

### TEST

- 2019-02-21 Debian9 Stretch backup to NTFS usb storage pass

If you have any trouble with backup success or failure, please submit result in Issues to help me improve script. Thanks.

### HOW TO USE IT

```sh
git clone https://github.com/cuifeiran/pi_bakup.git 
cp pi_bakup
sh bak.sh 
```

And then,choose1：backup piSD>first USB storage（Default :/dev/sda1）. if your pi system in USB storage,choose2:backup piUSB >second USB storage（Default:/dev/sda2）

*other demand please revise the code by yourself*
### NOTES
Because backup time is too long, if SSH is used, its default timeout configuration item may cause backup interruption. It is recommended to modify the default timeout time of SSH or install screen.Reference resources:[Dave's CSDN](https://blog.csdn.net/qq_33273956/article/details/87618350)

The backup process usually takes more than 20 minutes. ~~The progress will not be displayed when the backup process is executed to part1. Please wait patiently.~~


### UPDATE
2019-02-21 update：part1 createing img shows progress

2019-02-21 change：create img size 1.3 multiple to 1.5 multiple


### REFERENCE RESOURCES： 
>[conanwhf/RaspberryPi-script](https://github.com/conanwhf/RaspberryPi-script)

  - Thank your predecessors for giving! (The reason why there is no forked is that the script may have been worsened by me. I didn't want to pollute the master, so I built a new warehouse. )
