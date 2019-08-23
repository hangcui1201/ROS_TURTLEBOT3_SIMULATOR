## Quick Setup for Turtlebot3 Simulation

### ROS version: Kinetic (Ubuntu 16.04)

#### House Map

$ roslaunch turtlebot3_gazebo turtlebot3_house.launch  
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=/home/hang/ros/tb3_house_map.yaml  
