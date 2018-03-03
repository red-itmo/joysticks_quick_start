cmake_minimum_required(VERSION 2.8.3)
project(joysticks_quick_start)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED)

include_directories(${catkin_INCLUDE_DIRS})

catkin_package()
