# SLAM-with-Turtlebot-2-and-RealSense-D435i

If you want to use the turtlebot 2 with d435i camera, it is necessary to modify the following ROS packages:

  -turtlebot_description
  
  -turtlebot_bringup
  
  -turtlebot_navigation

In these packages, additional files for the RealSense d435i model have been included. 
In addition, the "3dsensor.launch" file has been modified so that the depth image can be correctly converted into a laser using the depthimage_to_laserscan package.
