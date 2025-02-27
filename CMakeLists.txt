# Description: CMakeLists.txt for the shunk_gripper_description package
# Author : Myeong Jin Lee
# Date : 2025-02-27

cmake_minimum_required(VERSION 3.0.2)
project(shunk_gripper_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY meshes urdf launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
