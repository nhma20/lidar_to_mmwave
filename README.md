# lidar_to_mmwave
Simple conversion of 2D lidar rays to noisy mmWave for Gazebo simulation

Subscribes to `/dist_sensor/laser_scan` topic from a Gazebo libgazebo_ros_ray_sensor.so 2D lidar plugin, groups points, adds noise, and publishes as `/lidar_to_mmwave_pcl` topic.

## Run
Source ROS2 and workspace, then run:
```
ros2 run lidar_to_mmwave lidar_to_mmwave_node 
```
