cmake_minimum_required(VERSION 3.20)
project(Track)

set(CMAKE_CXX_STANDARD 20)

add_executable(Track PriceTracker.h User.h Main.cpp User.cpp)
