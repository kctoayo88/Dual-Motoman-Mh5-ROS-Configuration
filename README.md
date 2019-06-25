# Dual_Motoman_Mh5_ROS_Configuration
The basic ROS configuration of dual motoman mh5.

## How to launch it

```roslaunch clear_dual_motoman_mh5_moveit_config motoman_mh5_planning_execution.launch robot_ip:=[IP_Address] controller:=[Controller_model]```

## Enable the robots
```rosservice call /robot_enable```
