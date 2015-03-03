cmake_minimum_required(VERSION 2.8.3)
project(guardian_terabot_description)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  guardian_description
  terabot_description
)

catkin_package(

)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

