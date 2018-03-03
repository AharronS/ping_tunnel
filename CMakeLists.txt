cmake_minimum_required(VERSION 3.5)
project(ICMP_tunnel)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(ICMP_tunnel ${SOURCE_FILES})