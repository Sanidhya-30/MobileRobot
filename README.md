# Mobile Robot
Repository of Mobile Robot capable of Autonomous navigation and mapping.

## Key Feature:-
* multiple purposes AMR.
* Wall following algorithm using LiDAR data
* Automated mapping of the environment 
* Performs SLAM

<!--## Electro-mechanical design:

* Drone frame.
![Image alt text](Media/Capture1-removebg-preview.png?raw=true "Drone frame")


## Flight Controller Schematic:
![Image alt text](Media/sch.PNG?raw=true "Schematic")

## ROS Packages:
* [SkyLark package](#flying_skylark)-->

### Running Sim
------------------
* This package contains all the files related to the robot and its configuration 

### Setup and launching the simulation environment:-

* Clone the repo, and build using catkin_make.
```
cd MobileRobot
catkin_make
source ~/{name_of_workspace}/devel/setup.bash
```

* Command `roslaunch mobile_robot test.launch` will launch the gazebo world along 


### Simulation Video
Click on Image to play
![https://drive.google.com/file/d/1OH6szEyb7mijPEnPgMssP5QMQEAGl-JM/view?usp=drive_link](https://drive.google.com/file/d/1TIgbr7hFeYiUMQglbhnqZhLON5erhb4r/view?usp=drive_link)


## Prerequisites
* C++14
* python 3.x
* ROS Noetic
* Raspberry pi 3B
