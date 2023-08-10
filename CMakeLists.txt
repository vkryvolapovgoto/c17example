cmake_minimum_required(VERSION 3.5)

project(c17example)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(c17example main.cpp)