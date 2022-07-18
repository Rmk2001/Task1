# Task1
for smart method training

**Step to install ROS on linux**
1-download virtualbox
2-install ubunto
3-install ROS in ubunto
 -**Setup your sources.list**
Setup your computer to accept software from packages.ros.org.


sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

 -**Set up your keys**
 sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6F8AB17C654
 
 -**Installation**
 First, make sure your Debian package index is up-to-date:

sudo apt update

 -**Now pick how much of ROS you would like to install.**
 Desktop-Full Install: (Recommended) : Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages

sudo apt install ros-noetic-desktop-full

 -sudo apt install ros-noetic-PACKAGE
