# Dual_Motoman_Mh5_ROS_Configuration
The basic ROS configuration of dual motoman mh5

## How to launch it

```roslaunch clear_dual_motoman_mh5_moveit_config motoman_mh5_planning_execution.launch robot_ip:=192.168.0.20 controller:=fs100```

## Enable the robots
```rosservice call /robot_enable```
