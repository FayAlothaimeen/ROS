# ROS

Steps to install ROS:

1- First, you need to install Virtual Box, go to Google search for  Virtual Box
installation, and then download it and make sure that suitable for your computer.

![IMG 1](Images/IMG 1.jpg)

2-second, you need to download Ubuntu just go to Google and download it.
![IMG 2](Images/IMG 2.jpg)
3- after  that, open the terminal to set up the Ubuntu systeam and write :

sudo apt update

after that write :

sudo apt upgrade

![IMG 3](Images/IMG 3.jpg)

4-Third, to download ROS  go to Google and search for ROS download and copy the line code to setup your sources.list
![IMG 4](Images/IMG 4.jpg)
5-similarity for setup your Keys
![IMG 5](Images/IMG 5.jpg)
6- then write sudo apt - get update

7-after that you have 3 option to downlod ROS :

1-Desktop-Full Instal: Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages
2-Desktop Install: Everything in ROS-Base plus tools like rqt and rviz
3-ROS-Base: ROS packaging, build, and communication libraries. No GUI tools.
copy anyone option that suitable for you
![IMG 6](Images/IMG 6.jpg)
8- the last on is Environment setup, You must source this script in every bash terminal you use ROS in.
just write this code : source /opt/ros/noetic/setup.bash
![IMG 7](Images/IMG 7.jpg)
