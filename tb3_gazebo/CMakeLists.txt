cmake_minimum_required(VERSION 2.8.3)
project(tb3_gazebo)
add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  gazebo_ros
  geometry_msgs
)

catkin_package(
  INCLUDE_DIRS
  LIBRARIES
  CATKIN_DEPENDS
    roscpp
    gazebo_ros
    geometry_msgs
  DEPENDS
)
