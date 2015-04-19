cmake_minimum_required(VERSION 3.1)

set(SOURCE_FILES basic/src/main.cpp)
add_executable(opencv_sandbox ${SOURCE_FILES})
target_link_libraries( opencv_sandbox ${OpenCV_LIBS} )