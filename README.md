# hector_mapping_rplidar

mapping of an indoor environment using hector mapping method.

To run the code clone the repository into your ros workspace.

Then run the following code in a new terminal
`$ catkin_make'
`$ roslaunch hector_slam_launch rplidar_mapping.launch `

Here we use the rplidar s1 lidar for the mapping process.

The hector mapping package can is taken from  https://github.com/tu-darmstadt-ros-pkg/hector_slam

rplidar driver package you can also find in https://github.com/Slamtec/rplidar_ros
