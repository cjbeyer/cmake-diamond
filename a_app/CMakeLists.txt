cmake_minimum_required(VERSION 3.6)
set(CMAKE_VERBOSE_MAKEFILE on)

add_executable(a a.cpp)

target_link_libraries(a b c)
