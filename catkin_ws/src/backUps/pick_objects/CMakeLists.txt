cmake_minimum_required(VERSION 2.8.3)
project(pick_objetcs)


find_package(
 catkin REQUIRED COMPONENTS
 actionlib
 move_base_msgs
 roscpp	
)

catkin_package(
 INCLUDE_DIRS include
 LIBRARIES pick_objects
 CATKIN_DEPENDS actionlib move_base_msgs rosscpp
 DEPENDS system_lib
)

include_directories(
 ${catkin_INCLUDE_DIRS}
)

add_executable(${PROJECT_NAME} src/pick_objects.cpp)

target_link_libraries(
 ${PROJECT_NAME}
 ${catkin_LIBRARIES}
)

