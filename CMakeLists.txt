cmake_minimum_required(VERSION 3.9.2)
project(super-machine-ball)


#################################################
# COMPILER SETTINGS
#################################################
set (CMAKE_CXX_FLAGS            "-std=c++11")


#################################################
# BUILD SETTINGS
#################################################
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)


add_subdirectory(src)