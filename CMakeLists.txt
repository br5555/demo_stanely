cmake_minimum_required(VERSION 2.8.3)
project(demo_stanley)

find_package(catkin REQUIRED COMPONENTS
  cmake_modules
  geometry_msgs
  nav_core
  nav_msgs
  roscpp
  roslib
  rviz
  std_msgs
  tf
  tf2
  tf2_geometry_msgs
  tf2_kdl
  tf2_msgs
  tf2_py
  tf2_ros
  tf2_tools
)


include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)


