cmake_minimum_required(VERSION 3.6)
set(CMAKE_VERBOSE_MAKEFILE on)

add_library(b STATIC b.cpp)
target_include_directories(d PUBLIC .)
target_link_libraries(b d)
