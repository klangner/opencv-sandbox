cmake_minimum_required(VERSION 3.1)
project(opencv_sandbox)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp)
add_executable(opencv_sandbox ${SOURCE_FILES})