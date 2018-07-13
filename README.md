# Multiple_turtlebots

IMPORTANT: This package is outdated and don't perform well. Updated repo is private now due to code privacy policy. Please refer to this [issue](https://github.com/AufarZakiev/Multiple_turtlebots/issues/1) for the implementation advices. Updated repo will be published at the paper printing time.

## Overview
This is launch files used to spawn multiple Turtlebots in single Gazebo simulation with AMCL and goal navigation performed.

## How to use
To launch simulation with multiple Turtlebots:
```sh
roslaunch multiple_turtlebots multiple_turtlebot_world.launch
```

To add them AMCL algorithms and move bases:
```sh
roslaunch multiple_turtlebots amcl_wo_map.launch
```

To view navaigation and AMCL results:
```sh 
roslaunch multiple_turtlebots view_navigation.launch
```
