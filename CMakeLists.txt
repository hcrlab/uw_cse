cmake_minimum_required(VERSION 2.8.3)
project(uw_cse)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
)

catkin_package()

install(DIRECTORY launch models worlds maps
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

