
# NUS ARC Summer Project 2020

 1. Brief Overview 
 2. Gazebo Environment
 3. Gazebo Robot 
 4. Dependencies 

## 1. Brief Overview
This documentation includes a list of commands to initiate the simulation of an indoor office environment in Gazebo, using the Clearpath Husky Robot. 

2. Gazebo Environment
start with roscore 

## 3. Gazebo Robot
Upon launching the environment, the following section will cover spawning husky into the gazebo, launching it in Rviz and controlling it with Teleop commands. 

Spawn Husky into Gazebo
To spawn husky, ensure that you have sourced the src file to devel/setup. Then, simply use the following command:

    roslaunch robot_gazebo spawn_husky.launch

 Once husky is launched inside Gazebo, you can launch another terminal and proceed to visualize it in Rviz using this command:

    roslaunch robot_rviz view_robot.launch

Finally, to control it's movement inside Gazebo, launch another terminal to control it using the following command:

    rosrun random_husky_driver random_driver
This is a 
5. Dependencies 
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTAyOTEyMDczLC05MjU4Njc2MzYsMTg2Mj
UwOTcwNV19
-->