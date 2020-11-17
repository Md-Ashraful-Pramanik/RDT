cmake_minimum_required(VERSION 3.17)
project(RTP)

set(CMAKE_CXX_STANDARD 14)

add_executable(RTP main.cpp)
add_executable(rdt rdt.c)
add_executable(color_printer color_printer.c)