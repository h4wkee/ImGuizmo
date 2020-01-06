cmake_minimum_required(VERSION 3.15)
project(imguizmo)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SRC_FILES *.cpp)

add_library(imguizmo STATIC ${SRC_FILES})