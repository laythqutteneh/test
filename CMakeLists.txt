cmake_minimum_required(VERSION 3.25)
project(test C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(test
        main.c)
