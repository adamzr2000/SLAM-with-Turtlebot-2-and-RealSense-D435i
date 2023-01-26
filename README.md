# SLAM-with-Turtlebot-2-and-RealSense-D435i

In order to do navigation tasks with turtlebot 2 and d435i camera, it is necessary to modify the following ROS packages:

  -turtlebot_description
  
  -turtlebot_bringup
  
  -turtlebot_navigation

These packages contains additional files for the RealSense d435i model. 
In addition, the "3dsensor.launch" file has been modified so that the depth image can be correctly converted into a laser using the depthimage_to_laserscan package.
