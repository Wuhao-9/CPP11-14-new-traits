cmake_minimum_required(VERSION 3.5)

project(01_hardware_concurrency)

set(${CMAKE_CXX_STANDARD} "-std=c++11")

link_libraries("-lpthread")

add_executable(${CMAKE_PROJECT_NAME} main.cpp)
