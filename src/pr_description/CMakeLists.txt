cmake_minimum_required(VERSION 3.0.2)
project(pr_description)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)