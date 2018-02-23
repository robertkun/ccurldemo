cmake_minimum_required(VERSION 3.5)
project(ccurldemo)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES source/main.cpp)
add_executable(ccurldemo ${SOURCE_FILES})