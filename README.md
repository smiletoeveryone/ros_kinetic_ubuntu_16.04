![](https://github.com/smiletoeveryone/headless_raspberry_pi4/blob/master/raspbian%20os%20installation%20tutorial%20without%20a%20monitor.bmp)
install ros kinetic on ubuntu 16.04(xenial) with 9 steps only

1.Setup your sources.list

sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

2.Set up your keys

sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

3.Installation

sudo atp update

Desktop-Full Install:

sudo apt-get install ros-kinetic-desktop-full

4.sudo rosdep init

5.rosdep update

6.echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc

7.source ~/.bashrc

8.source /opt/ros/kinetic/setup.bash

9.Dependencies for building packages

sudo apt install python-rosinstall python-rosinstall-generator python-wstool build-essential
