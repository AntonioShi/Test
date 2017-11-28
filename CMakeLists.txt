cmake_minimum_required(VERSION 3.8)
project(Test)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp skipist.cpp skiplist.h)
add_executable(Test ${SOURCE_FILES} skipist.cpp skiplist.h)