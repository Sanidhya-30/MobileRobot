# Mobile Robot
Repository of Autonomous Mobile Vehicle named MoRo capable of navigation and mapping.

## Key Feature:-
* Autonomous robot with payload to carry for multiple purposes which is capable to move on RC control.
* Manipulate flight by gesture recognition.

<!--## Electro-mechanical design:

* Drone frame.
![Image alt text](Media/Capture1-removebg-preview.png?raw=true "Drone frame")


## Flight Controller Schematic:
![Image alt text](Media/sch.PNG?raw=true "Schematic")

## ROS Packages:
* [SkyLark package](#flying_skylark)-->

### Running Sim
------------------
* This package contains all the files related to robot and its configuration 

### Setup and launching the simulation environment:-

* Clone the repo, build using catkin_make.
```
cd MobileRobot
catkin_make
source ~/{name_of_workspace}/devel/setup.bash

```

* Command `roslaunch mobile_robot test.launch` will launch the gazebo world along 


### Simulation Video
Click on Image to play
[![Watch the video](https://drive.google.com/file/d/14UZnkJskSmzBEio8NkAA1Ng_3ccjfzua/view?usp=sharing)](https://drive.google.com/file/d/14UZnkJskSmzBEio8NkAA1Ng_3ccjfzua/view?usp=sharing))


## Prerequisites
* C++14
* python 2.x
* PX4 AutoPilot
* ROS Noetic
* Embedded C
* Raspberry pi 3B (setup given below)
