# hephaestus_msgs
This repo contains customized message and service interfaces for Hephaestus related projects.

## 1. Prerequisites
* Ubuntu 20.04.
* ROS Noetic.

## 2. Install this package.
```sh
cd <your_ws>/src
git clone https://github.com/purimagination/hephaestus_msgs.git
cd ..
rosdep install--from-pathsrc--ignore-src-r -y
catkin_make
```