cmake_minimum_required(VERSION 3.3)
project(raycaster)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES raycaster.c)
add_executable(raycaster ${SOURCE_FILES})