cmake_minimum_required(VERSION 3.17)
project(RTP)

set(CMAKE_CXX_STANDARD 14)

add_executable(RTP rdt.c)
add_executable(color_printer_windows color_printer_windows.c)
add_executable(color_printer_linux color_printer_linux.c)