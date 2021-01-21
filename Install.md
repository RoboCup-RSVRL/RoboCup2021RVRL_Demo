# How to install ROS(melodic) and gazebo9.  

$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'   
$ sudo apt-key adv --keyserver hkp://pool.sks-keyservers.net --recv-key 0xB01FA116   
$ sudo sh -c 'echo "deb http://packages.osrfoundation.org/gazebo/ubuntu `lsb_release -cs` main" > /etc/apt/sources.list.d/gazebo-latest.list'   
$ wget http://packages.osrfoundation.org/gazebo.key -O - | sudo apt-key add -     
$ sudo apt-get update   
$ sudo apt-get install -y cmake g++ protobuf-compiler pavucontrol gazebo9-plugin-base libgazebo9 libgazebo9-dev ros-melodic-desktop  ros-melodic-ros-control ros-melodic-ros-controllers ros-melodic-image-view2 ros-melodic-rqt ros-melodic-rqt-common-plugins ros-melodic-joy ros-melodic-teleop-twist-keyboard ros-melodic-message-to-tf ros-melodic-tf2-geometry-msgs ros-melodic-audio-common ros-melodic-costmap-2d ros-melodic-image-transport ros-melodic-image-transport-plugins ros-melodic-hector-mapping ros-melodic-hector-geotiff 
$ sudo apt-get install ros-melodic-hector-sensors-description ros-melodic-controller-manager ros-melodic-gmapping ros-melodic-move-base ros-melodic-hector-mapping ros-melodic-gazebo9*
