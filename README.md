Raspberry-Pi-CPS-SN-trial
=========================

This is a raspbian image support CPS virtualize environment for implement sensor and actuator network flexible on the web. It is simple environment for education and non-profit objective embedded Linux kernel image. The image is trail and backup with non-profit propose. The environment is automatively running with Blue-sky cloud server. We will not responding anymore with the people who use this image with another ojective written above.

The environment shows that how we can implement the bridge environment about sensor and actuator network to flexible, robustness on the web from small scale to large scale of such environment. Because, the environment is now developing, I am very glad to welcome the people who love to develop it together. Please, contact me directly.

Get Started
===========
The kernel is coorperated with [BlueSky cloud](https://github.com/not001praween001/BlueSkyLoggerCloudBINResearchVer1.0).The preparation has two side below.

・ Server side. See the [BlueSky cloud](https://github.com/not001praween001/BlueSkyLoggerCloudBINResearchVer1.0).
・ Embedded Device side. See the next step.


Download or clone git
-------------------------

$> git clone https://github.com/not001praween001/Raspberry-Pi-CPS-SN-trial.git

$> cd Raspberry-Pi-CPS-SN-trial


Image preparation (Burning Raspberry-Pi-CPS kernel)
---------------------------------------------------

The image is splited compressing data file. You can merge all splited file by "cat" on Linux environment. Then, uncompressed image file to your harddrive. The raw image file name is "RaspberryPi-SN-backup_20121030". You can burn it to your RaspberryPis SD card. Image file size is 8GB.

$> cat RaspberryPi-SN-backup_20121030.tgz.* > RaspberryPi-SN-backup_20121030.tgz

$> tar -xvf RaspberryPi-SN-backup_20121030.tgz

$> sudo dd if=RaspberryPi-SN-backup_20121030 of=/dev/sdX bs=1M

X is device name. The SD Memory Card capacity should be more than 8GB.

Login
-------------------------

Insert your burned SD card into your Raspberry Pis. Then, plug your pi electric power and HDMI cable.

You can login via both tty serial and SSH.

User name: pi

Password: raspberry
