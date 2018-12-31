# SAPiObjectDetection

Portable and demonstrative Food recognizer & Object Detection system on Raspberry Pi 3

### Overview
<p align="center">
  <img src="./images/overview.jpg">
</p>

Minimal requirements:
  * [x] Supply -> Powerbank
  * [x] Input -> Pi Camera
  * [x] OS -> Ubuntu Mate (Raspbian)
  * [ ] Software -> Nanonet?, PyImageSearch?
  * [x] Output -> LCD 3.5 inch screen

### How to do:

1) Setup OS:
  * [Download Ubuntu Mate](https://ubuntu-mate.org/raspberry-pi/)
  * [Setup](https://roboticsweekends.blogspot.com/2017/12/how-to-install-ros-on-raspberry-pi-2-or.html)  
  * Determine SD Card (for me: /dev/mmcblk0) and flash SD Card:

```
fdisk -l
cd Downloads
xzcat ubuntu-mate-16.04.2-desktop-armhf-raspberry-pi.img | sudo dd bs=4M of=/dev/mmcblk0
sudo fdisk -l /dev/mmcblk0
```

  * Plug SD Card into Raspberry Pi 3 and boot it up

```
sudo apt-get update
sudo apt-get upgrade
```

2) Run Software:
  * PyImageSearch
  * Nanonet
  
3) Install LCD Screen:
  * https://github.com/goodtft/LCD-show

### Goal
<p align="center">
  <img src="./images/example.jpg">
</p>
Label: Buddha Bowl


