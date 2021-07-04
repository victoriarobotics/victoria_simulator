[![Build Status](https://travis-ci.org/victoriarobotics/victoria_simulator.svg?branch=master)](https://travis-ci.org/victoriarobotics/victoria_simulator)
# victoria_simulator
Gazebo simulation of the Victoria Platform.

# Requirements:

- ROS Kinetic
- Gazebo 7
- ros-kinectic-filters
- ros-kinectic-laser-geometry
- victoria_base https://github.com/victoriarobotics/victoria_base
- victoria_ros https://github.com/victoriarobotics/victoria_ros

# How to:

To launch victoria robot on an empty world:

```
$ roslaunch victoria_gazebo victoria_empty_world.launch
```

To launch victoria robot on the test world:

```
$ roslaunch victoria_gazebo victoria_test_world.launch 
```
