Fusion 360 to URDF - https://github.com/dheena2k2/fusion2urdf-ros2

Guide to starting URDF Fusion Model

cd /Prototype1/src
source install/setup.bash
Now either
ros2 launch (whatever your robot_name is)_description display.launch.py
or
ros2 launch (whatever your robot_name is)_description gazebo.launch.py