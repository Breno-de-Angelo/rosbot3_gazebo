# rosbot3_gazebo

Utilities for simulating the ROSbot3 robot.

This package uses the definition of the ROSbot3 from the [rosbot3_description package](https://github.com/Breno-de-Angelo/rosbot3_description) and adds gazebo extra informations.

Using the [start.launch](./launch/start.launch) script, a ROSbot3 is spawned in a Willow Garage world, defined [here](./worlds/willow_garage.world). The launch file also opens RVIZ and RQT with usefult visualization settings for the user to control the robot and read the sensor data.

The robot is controlled using a skid controller from gazebo defined in  [ros_commons package](https://github.com/Breno-de-Angelo/ros_commons).


