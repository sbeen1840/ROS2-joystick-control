# joystick_ros2

## Install
```
# with ROS2 already sourced
$ cd <ros2_workspace>/src
$ git clone https://github.com/sbeen1840/joystick_ros2
$ cd ..
$ colcon build

# for Linux / OS X
$ source install/local_setup.bash

# for Windows
$ call install/local_setup.bat
```

## Usage
- Plug in the joystick
- Run the node with below command
    ```
    $ ros2 run joystick_ros2 joystick_ros2
    ``` 

## Supported joysticks
Windows:

    - All Xinput Controller

Linux, Mac OSX:

    - PS4 Controller
    - Logitech F710
    - Xbox One Controller

## Published Topics
- joy ([sensor_msgs/Joy](https://github.com/ros2/common_interfaces/blob/master/sensor_msgs/msg/Joy.msg))


