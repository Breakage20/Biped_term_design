# Biped simulation 

## Table of Contents
* [Instalation of Robot Operating System](#instalation-of-robot-operating-system)
* [Create workspace](#create-workspace)
* [Simulation environment](#run-simulation)
* [Tasks](#what-should-be-done)



## Instalation of Robot Operating System
![ROS Instalation Tutorial](http://wiki.ros.org/noetic/Installation/Ubuntu)
## Create workspace
```
$ git clone https://github.com/Breakage20/Biped_term_design.git
$ cd Biped_term_design
$ catkin_make
```
## Run simulation 
```
$ roscore
```
Open your workspace and in seperate terminal run
```
$ source devel/setup.bash
$ roslaunch biped_gazebo biped_world.launch 
```

## What should be done
#### Calculate inverse kinematics of the leg knowing that:
* hip length = 165mm
* knee length = 240mm

#### Write simple python script based on your formulas

The input of the script should be a position of foot in cartesian space and the output should be in radians.




### ...............................................
This repo as well as the tasks  wil be updated in the future
