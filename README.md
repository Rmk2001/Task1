# Task1
for smart method training

**Step to install ROS on linux**


 **Step 1 :**download virtualbox


**Step 2 :**install ubunto


**Step 3 :**install ROS in ubunto


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
 
 **Close this terminal and oppen new one**
 
 
 **Environment setup**
 
 source /opt/ros/noetic/setup.bash
 
 
 **and write**roscore
 
 
 # install ROS2 on Jeston nano
 
 
 **Step 1>>**download Xubunto20.4
 
 
 **Step 2>>**oppen virtualbox and click <new> 
 
 
 **Step 3>>**upload xupunto file
 
 
 **Step 4>>**cuntinio setting
 
 
 **oppen terminal and install ROS2**
 
 
 1>>locale  # check for UTF-8

sudo apt update && sudo apt install locales
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8

locale  # verify settings
 
 
 2>>apt-cache policy | grep universe
 
 
 3>>500 http://us.archive.ubuntu.com/ubuntu focal/universe amd64 Packages
    release v=20.04,o=Ubuntu,a=focal,n=focal,l=Ubuntu,c=universe,b=amd64
 
 
 4>>sudo apt install software-properties-common
sudo add-apt-repository universe
 
 
 5>>udo apt update && sudo apt install curl gnupg2 lsb-release
sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key  -o /usr/share/keyrings/ros-archive-keyring.gpg
 
 
 6>>echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/ros-archive-keyring.gpg] http://packages.ros.org/ros2/ubuntu $(source /etc/os-release && echo $UBUNTU_CODENAME) main" | sudo tee /etc/apt/sources.list.d/ros2.list > /dev/null
 
 
 7>>sudo apt update
 
 
 8>>sudo apt upgrade
 
 
 9>>sudo apt install ros-foxy-desktop
 
 
