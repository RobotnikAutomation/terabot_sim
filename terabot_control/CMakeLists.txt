cmake_minimum_required(VERSION 2.8.3)
project(terabot_control)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  controller_manager
  controller_manager_msgs
  terabot_description
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES terabot_control
#  CATKIN_DEPENDS controller_manager controller_manager_msgs terabot_description
#  DEPENDS system_lib
)

###########
## Build ##
###########

## Specify additional locations of header files
## Your package locations should be listed before other locations
# include_directories(include)
include_directories(
  ${catkin_INCLUDE_DIRS}
)

