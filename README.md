# xl430_control
Clone this repository along with DynamixelSDK, Dynamixel Workbench, and Dynamixel Workbench Msgs Repositories, for which the commands are available on this link:
https://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_workbench/
Run the command catkin_make to build these ROS packages, source the devel/setup.bash file and then run this command in your workspace:
$ roslaunch xl430_control xl430_control.launch
You might need to configure your usb port, /dev/ttyUSB0, before running this command, and the dynamixel motors would obviously have to be connected to the port.
The configuration .yaml file for the Dynamixels and the launch file can be edited to change the baud rate, the number of motors, profile velocity and acceleration, etc.
