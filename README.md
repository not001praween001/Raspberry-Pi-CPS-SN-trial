Raspberry-Pi-CPS-SN-trial
=========================

This is a raspbian image support CPS virtualize framework environment for implement sensor and actuator network flexible on the web. It is simple environment for education and non-profit objective embedded Linux kernel image. The image is trail and backup propuse. This framework is running well with Blue-sky cloud server. We will not responding anymore for the people who use this image with another ojective written above.

The framework shows that how we can implement the bridge framework about sensor and actuator network to flexible, robustness on the web.

Download or clone git
-------------------------

$> git clone https://github.com/not001praween001/Raspberry-Pi-CPS-SN-trial.git

$> cd Raspberry-Pi-CPS-SN-trial


Image prepare
-------------------------

The image is splited compressing data file. You can merge all splited file by "cat" on Linux environment. Then, uncompressed image file to your harddrive. The raw image file name is "RaspberryPi-SN-backup_20121030". You can burn it to your RaspberryPis SD card. Image file size is 8GB.

$> cat RaspberryPi-SN-backup_20121030.tgz.* > RaspberryPi-SN-backup_20121030.tgz

$> tar -xvf RaspberryPi-SN-backup_20121030.tgz

$> sudo dd if=RaspberryPi-SN-backup_20121030 of=/dev/sdX bs=1M

X is device name. The device should more than 8GB.

Login
-------------------------

Insert your burned SD card into your Raspberry Pis. Then, plug your pi electric power and HDMI cable.

You can login via both tty serial and SSH.

User name: pi

Password: raspberry