# Introduction
The codes in this repository is a reimplementation of the ROS projects in the tutorial Exploring ROS using a two-wheeled robot by Marco Arruda. It is a very nice tutorial on ROS, which uses a two-wheeled robot to show the features and tools provided by ROS. In the tutorial, you will learn

Building a robot using URDF and Xacro
Simulating a robot in Gazebo
Develop motion plan algorithms for a robot
The tutorial uses an online ROS Development tool - ROS Development Studio (ROSDS) by the Construct to create the ROS packages. To use ROSDS, you need to create an account on the Construct. Depending on your network speed, running ROS packages in ROSDS may be slow.

By using the codes in this repository, you can run the ROS packages in your local machines provided that you have ROS installed.

The packages are tested on ROS Noetic Ninjemys.

# Usage
Clone the codes

git clone https://github.com/Humayun-Akhtar/ROS_2_wheeled_robot_in_Gazebo.git
Build the ROS packages

cd Two_Wheeled_Robot_ROS_Tutorial
catkin build
source ./devel/setup.bash
Follow the tutorial here to explore ROS. You wil need to checkout the earlier commits and rebuild the packages to follow each part of the tutorial.

#References
The codes in the tutorial for ROSDS are available on Bitbucket.

https://bitbucket.org/theconstructcore/two-wheeled-robot-motion-planning/src/master/scripts/

https://bitbucket.org/theconstructcore/two-wheeled-robot-simulation/src/master/
