cmake_minimum_required(VERSION 3.29)
project(hello C)

set(CMAKE_C_STANDARD 11)

add_executable(hello hello.c
        numbers.c
        donut.c)
