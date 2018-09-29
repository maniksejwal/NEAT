cmake_minimum_required(VERSION 2.4)

PROJECT(neat)

FILE(GLOB neat_sources *.cpp)
set(CMAKE_CXX_STANDARD 98)

ADD_EXECUTABLE(neat ${neat_sources})
