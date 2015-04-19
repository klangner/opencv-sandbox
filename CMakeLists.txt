cmake_minimum_required(VERSION 3.1)
project(opencv_sandbox)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
find_package( OpenCV REQUIRED )

include(${CMAKE_CURRENT_SOURCE_DIR}/basic/CMakeLists.txt)