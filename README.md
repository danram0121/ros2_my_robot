# ros2_my_robot

## Description

This repo contains the URDF and launch files for the custom robot I have begun designing

## Install

1st create a new directory in your Home Directory originally I named mine ros2_robot_ws

```
cd
mkdir ros2_robot_ws
```

then i created a src file inside that new ros2_robot_ws

```
cd ros2_robot_ws
mkdir src
```

then I created my ROS2 workspace

```
cd
cd ros2_robot_ws
colcon build --symlink-install
```

you should be able to clone this repo to your new src directory

```
git clone https://github.com/danram0121/ros2_my_robot.git
```

## Dependencies

- Colcon
- TBD
