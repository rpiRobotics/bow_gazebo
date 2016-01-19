# bow_gazebo
ROS package to run baxter on ridgeback mobile robot on gazebo.

This package is to visualize the Baxter on Ridgeback in gazebo:

1. download bow_gazebo package:
https://github.com/rpiRobotics/bow_gazebo

2. download bow_description package and required dependencies from:
https://github.com/rpiRobotics/bow_description

3. catkin_make in ros workspace directory

4. source devel/setup.bash

5. roslaunch bow_gazebo bow_world.launch

6. Write to topic /cmd_vel to control mobile base.

7. Follow instructions on baxter simulator sdk page to command baxter manipulator.

Since the implementation of ridgeback simulator is incomplete, the mobile base might not function properly.
