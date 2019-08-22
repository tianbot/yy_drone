# About yy_drone

This meta-package is forked from 

https://github.com/paulyang1990/toy_code/tree/master/toy_ros_space/src/sim_drone

Compiled successfully in ROS kinetic Ubuntu 16.04.

run depend on Joy.

Article for Kaka from zhihu.com (YY硕) https://zhuanlan.zhihu.com/p/35862380
Online Video Course in Chinese for Kaka (Registration required)
https://www.aiimooc.com/mall/show-htm-itemid-395-chapterNo-3-segmentNo-3.html


# Quick Steps
The video course will be in detail and if you are quite familiar with ROS just follow the command lines.
You need to prepare a Logitech F710 gamepad or an alternative.

## Install required packages. git and joy
```
sudo apt-get install git
sudo apt-get install ros-kinetic-joy
```
## Download the repo and compile
```
cd ~/catkin_ws/src
git clone https://github.com/tianbot/yy_drone
cd ..
catkin_make
```

## Launch the sim drone
to guarantee you can find the package, execute package indexing first.

```
rospack profile
```
assume your gamepad is /dev/input/js0 just simply launch
```
roslaunch sim_drone test_kaka.launch
```
enjoy!

