# SAPiObjectDetection

Portable and demonstrative Food recognizer & Object Detection system on Raspberry Pi 3

### Overview
<p align="center">
  <img src="./images/overview.JPG">
</p>

Minimal requirements:
  * [x] Supply -> Powerbank
  * [x] OS -> Raspbian
  * [x] Output -> LCD 3.5 inch screen
  * [x] Input -> Pi Camera
  * [ ] Software -> Nanonet?, PyImageSearch?

### How to do

#### OS

1) [Download Raspbian Desktop](https://www.raspberrypi.org/downloads/raspbian/) and unzip it
2) [Flash SD Card](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md)

```
fdisk -l # (for me: /dev/mmcblk0)
cd Downloads
sudo dd bs=4M if=2018-11-13-raspbian-stretch-full.img of=/YOUR/SDCARD conv=fsyncsudo fdisk -l /dev/mmcblk0
```

3) Plug SD Card into Raspberry Pi 3, boot it up and run:  

```
sudo apt-get update
sudo apt-get upgrade
```

#### Input


  
#### Output

* [Install LCD Screen](https://github.com/goodtft/LCD-show)


#### Software

* PyImageSearch
  * [OpenCV](https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/)
  * [Face Recognition](https://www.pyimagesearch.com/2018/06/25/raspberry-pi-face-recognition/)
* Nanonet

### Goal

<p align="center">
  <img src="./images/example.jpg">
</p>

Label: Buddha Bowl

### Other Sources

[ROS](https://roboticsweekends.blogspot.com/2017/12/how-to-install-ros-on-raspberry-pi-2-or.html)  
