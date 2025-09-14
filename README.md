### This repository is for running ros1 noetic nodes on STM32F1 microcontrollers

This package has been tested on STM32F103C8T6 BluePill and STM32F103C8T6 SmartBoard V2

```
$ sudo apt-get install ros-noetic-rosserial
$ mkdir -p stm32f1_ros/src
$ cd stm32f1_ros/src
$ git clone https://github.com/venki666/stm32f1-ros
$ cd ..
$ catkin_make
$ source ~/stm32f1_ros/devel/setup.bash (setup.zsh)
$ cd <STM32CubeIDE_workspace>/<project>/Core/Inc
$ rosrun rosserial_stm32 make_libralies.py .
```
