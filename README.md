# ROS2_YOLOV5

System Requirements:

OS: Ubuntu 22.04

ROS Version: ROS Humble

Camera: Web Camera

Cuda version: 11.6 or Higher

GPU: Nvidia version with 1080 GPU

Python Libraries Requirements:

opencv and pytorch

Steps to Implement this Experiment:

Download the zip file from the following link into your system:(https://drive.google.com/file/d/1utRo7SezErKmg16vxmgAii1PxSQCJD_a/view?usp=sharing)

Unzip the zip file

After that run the following commands in your ubuntu linux system:

cd ws_yolov5/src

colcon build --symlink-install

pip3 install -r ./YOLOv5-ROS/requirements.txt

cd ws_yolov5/

source ./install/setup.bash

ros2 launch yolov5_ros yolov5s_simple.launch.py

Then after you can see the object detection for real time with your web camera.

