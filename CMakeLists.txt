cmake_minimum_required(VERSION 3.12)
project(CBS)

set(CMAKE_CXX_STANDARD 17)

add_library(CBS SHARED library.cpp library.h)