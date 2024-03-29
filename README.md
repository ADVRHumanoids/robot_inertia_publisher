robot_inertia_publisher
=======================

Overview
--------
The ```robot_inertia_publisher``` permits to broadcast and visualize in RVIZ inertial information retrieved from the URDF description of a robot.
Inertia of the single link is visualized as ellipsoid aorund a spehere which represents the cog of the link.

Node API
--------
### Published Topics
- ```link_inertias``` ([InertiaWithLinkArray][1])
- ```link_inertias_viz``` ([MarkerArray][2])
- ```total_mass``` ([Float32])
### Parameters
- ```robot_description``` (```String```, default: ```robot_description```)
- ```tf_prefix``` (```String```, default: None)

![Inertias and CoGs for COMAN](https://github.com/ADVRHumanoids/robot_inertia_publisher/blob/master/robot_inertia_publisher.png)

[1]: https://github.com/ADVRHumanoids/robot_inertia_publisher/blob/master/msg/InertiaWithLinkArray.msg "InertiaWithLinkArray"
[2]: http://docs.ros.org/melodic/api/visualization_msgs/html/msg/MarkerArray.html "MarkerArray"
