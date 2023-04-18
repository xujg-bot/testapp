cmake_minimum_required(VERSION 3.23)
project(testapp)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(testapp
        helloworld.cpp)
