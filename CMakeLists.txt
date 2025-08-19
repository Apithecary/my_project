cmake_minimum_required(VERSION 4.0)
project(my_project C)

set(CMAKE_C_STANDARD 11)

add_library(my_project STATIC library.c)
