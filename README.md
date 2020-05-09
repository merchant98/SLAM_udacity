# SLAM_udacity
Using vision sensors to create a map of an environment using the RTABmap Ros package. The Bot used has an RGB-D camera and hokuyo LIDAR as visionary sensors. Environment was created in Gazebo and the files can be found in the urdf folder.
I created an environment in Gazebo and a robot to be spawned in it.
Uses the turtlebot_teleop package to move the bot around. The rtab map works on loop closures, i.e recognizing a Landmark which it has alreay come across.
