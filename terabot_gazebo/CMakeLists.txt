cmake_minimum_required(VERSION 2.8.3)
project(terabot_gazebo)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
	terabot_description)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES terabot_gazebo
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

