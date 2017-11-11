cmake_minimum_required(VERSION 3.6)
set(CMAKE_VERBOSE_MAKEFILE on)

add_library(d STATIC d.cpp)
target_include_directories(d PUBLIC .)
