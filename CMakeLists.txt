cmake_minimum_required(VERSION 3.6)
project(AnEffectiveLoggerSystem)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES Logger.cpp)
add_executable(AnEffectiveLoggerSystem ${SOURCE_FILES})