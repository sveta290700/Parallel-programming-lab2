cmake_minimum_required(VERSION 3.17)
project(lab2)

set(CMAKE_CXX_STANDARD 20)

add_executable(generator source.cpp thread_num.cpp)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /std:c++20 /openmp")