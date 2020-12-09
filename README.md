# Tracking-a-ball using ROS

The goal of this project was to follow a white colored ball using a camera and differential mobile robot. In order to achieve this , a process_image node was created which subscibes to depth camera mounted on it and figures out for the presenece of the ball. Once after detecting the ball , 'drive_bot' node publishes joint wheel velecities to the mobile robot. 

Two primary packages were created in ROS to execute this task

1. myrobot - Contains urdf files of mobile robot , world file where the robot has be to housed in.
2. ball_chaser - Contains source files of 'process_image & 'drive_bot' node in C++.






