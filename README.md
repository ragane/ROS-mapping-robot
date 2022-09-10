# ROS-mapping-robot

![obraz](https://user-images.githubusercontent.com/62072813/187999788-103064bf-0849-4e4c-87d1-4aadbcb96da3.png)

Design of a non-holonomic, crawler robot developed in the ROS environment. 
It has two modes of motion:
- remote control from the user's computer by WiFi,
- moving along the walls according to the algorithm.

Simultaneously it uses SLAM technology for room mapping.

## Hardware
- Raspberry Pi 3B
- RPLidar A3M1
- Dual Motor Drive TB6612FNG
- Dagu Rover 5 Robot Chassis
- RPi Camera Arducam OV5647
- TP-LINK TL-WN722N
- 3 x Li-Ion 18650
- Powerbank 10000 mAh

## Software
- Ubuntu MATE 16.04 Xenial Xerus
- ROS Kinetic 16.04

## The robot uses great packages for the ROS environment
- Hector_slam - [GitHub Pages](https://github.com/tu-darmstadt-ros-pkg/hector_slam)
- Rplidar_ros -  [GitHub Pages](https://github.com/robopeak/rplidar_ros)

These packages provides necessary nodes in ROS to mapping room.

All processes are performed on RPI 3B.The user has access to the visualization and remote control of the robot thanks to the ROS network and WiFi connection.

# Sample rviz panel during room mapping
![obraz](https://user-images.githubusercontent.com/62072813/188001180-3781a4b1-d623-474e-af4f-c8752c1a9271.png)
