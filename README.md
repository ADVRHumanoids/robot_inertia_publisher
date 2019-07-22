robot_inertia_publisher
=======================

Overview
--------
The ```robot_inertia_publisher``` permits to broadcast and visualize in RVIZ inertial information retrieved from the URDF description of a robot.
Inertia is visualized as an ellipse aorund a spehere which represents the cog.

Node API
--------
### Published Topics
- ```link_inertias``` ([InertiaWithLinkArray][1])
- ```link_inertias_viz``` ([MarkerArray][2])
### Parameters
- ```robot_description``` (```String```, default: ```robot_description```)
- ```tf_prefix``` (```String```, default: None)

[1]: https://github.com/ADVRHumanoids/robot_inertia_publisher/blob/master/msg/InertiaWithLinkArray.msg "InertiaWithLinkArray"
[2]: http://docs.ros.org/melodic/api/visualization_msgs/html/msg/MarkerArray.html "MarkerArray"
