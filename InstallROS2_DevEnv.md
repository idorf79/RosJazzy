# Installing the ROS2 Jazzy on the development machine

Source: https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html


```
sudo apt install software-properties-common
sudo add-apt-repository universe
sudo apt update
sudo apt upgrade 
sudo apt install curl -y
sudo curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.key -o /usr/share/keyrings/ros-archive-keyring.gpg
```