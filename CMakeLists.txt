cmake_minimum_required(VERSION 2.8.3)
project(demo_stanley)

find_package(catkin REQUIRED COMPONENTS
  cmake_modules
  gazebo_msgs
  gazebo_plugins
  gazebo_ros
  gazebo_ros_control
  geometry_msgs
  nav_core
  nav_core
  nav_msgs
  nav_msgs
  pcl_conversions
  roscpp
  roslib
  rospy
  rviz
  std_msgs
  tf
  tf2
  tf2_bullet
  tf2_eigen
  tf2_geometry_msgs
  tf2_kdl
  tf2_msgs
  tf2_py
  tf2_ros
  tf2_sensor_msgs
  tf2_tools
  urdf
  xacro
)


include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)


