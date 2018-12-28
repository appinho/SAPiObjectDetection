# SAPiObjectDetection

A repository to build a remote Object Detection system for the own use of real-life traffic scenarios on a self-independent Raspberry Pi 3 system

## Installation


1) [Download Ubuntu Mate](https://ubuntu-mate.org/raspberry-pi/)
2) [Setup](https://roboticsweekends.blogspot.com/2017/12/how-to-install-ros-on-raspberry-pi-2-or.html)
a) Determine SD Card (for me: /dev/mmcblk0) and flash SD Card:

```
fdisk -l
cd Downloads
xzcat ubuntu-18.04.1-preinstalled-server-armhf+raspi2.img.xz | sudo dd bs=4M of=/dev/mmcblk0
sudo fdisk -l /dev/mmcblk0
```

b) Plug SD Card into Raspberry Pi 3 and boot it up

```
sudo apt-get update
sudo apt-get upgrade
```

3) [Raspi Cam Node](https://discourse.ros.org/t/raspberry-pi-camera-node/1388)

```
sudo apt install ros-kinetic-raspicam-node
```

## Other Sources

https://www.youtube.com/watch?v=VFuHG-Ho4Fk
