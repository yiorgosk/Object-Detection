# Object-Detection

An object detection application that uses a robot in order to recognise five gestures as Start, Stop, Reverse, Right, Left.
When the robot sees each gestures it moves forward, back, makes a reverse turn, rigt and left.
I used ROS in order to program the robot and train the model with Tensorflow Object Detection API.
The object detection can be performed with or without ROS

# Application without ROS

python object_detection.py

# Application with ROS

Not everyone has a real robot but in this case I used turtlebot 3 simulation for those who lack a real robot

The links in order to install ros and turtlebot 3 package are:

http://wiki.ros.org/melodic/Installation/Ubuntu
https://emanual.robotis.com/

roslaunch turtlebot3_gazebo turtlebot3_world.launch

python robot_vision.py

https://drive.google.com/drive/folders/1A32ysAWWKG6wf-Ogq6FnWbzxZNlX7mWq?usp=sharing
