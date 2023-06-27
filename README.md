# Object-detection-and-Obstacle-avoidance-using-YoloV5

Our project develops an environment with objects maze and several real time objects A bot moves in a maze and avoids obstacles and detects the objects of Environment using Yolov5 algorithm.YOLOv5 is a popular object detection algorithm that builds upon the previous versions of YOLO (You Only Look Once). It was developed by Ultralytics and introduced in 2020. YOLOv5 improves upon its predecessors by focusing on accuracy and speed, making it suitable for real-time object detection tasks.

# Pre-requisites
-Ubuntu 22.04

-ROS2 - Humble

-Python 3

-Yolov5

-Gazebo 11.10.2

# Commands
-colcon build (command is used to build ROS packages)

-source install/setup.bash (source the setup file to set the environment variables correctly)

-ros launch yolobot_gazebo yolobot_launch.py (launches the Gazebo simulation using the yolobot_launch.py launch file from the yolobot_gazebo package)

-python ros_recognition_yolo.py (script performs YOLO-based object recognition within the ROS framework)


# Simulation Visuals
-Real time Environment

![image](https://github.com/siddharth-39/Object-detection-and-Obstacle-avoidance-using-Yolo-V5/assets/135171824/6219c696-7363-40bf-ae33-4a1749935dea)

![image](https://github.com/siddharth-39/Object-detection-and-Obstacle-avoidance-using-Yolo-V5/assets/135171824/250246b9-5469-43fb-898a-a63e86743866)

-Object Detection using Yolo-V5

![image](https://github.com/siddharth-39/Object-detection-and-Obstacle-avoidance-using-Yolo-V5/assets/135171824/3ced87d6-6799-42e9-9197-81ee4065f53d)


# Demonstration Video
https://youtu.be/PzXebLfwQ4c

