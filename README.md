# hector_mapping_rplidar

In this package, mapping of an indoor environment using hector mapping method.

hector mapping is a node for LIDAR based SLAM with no odometry and low computational resources.

To use hector_mapping, we need a source of **sensor_msgs/LaserScan** data for that we use the **rplidar A2** lidar.

#### To run the code, clone the repository into your ros workspace.

Then run the following code in a new terminal

`$ catkin_make`

After successful make, we can run the following code. This lauch file contains the nodes to run both rplidar and mapping.

`$ roslaunch hector_slam_launch rplidar_mapping.launch `

#### Refrences

Hector Mapping:  https://github.com/tu-darmstadt-ros-pkg/hector_slam

rplidar driver: https://github.com/Slamtec/rplidar_ros
