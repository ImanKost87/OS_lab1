cmake_minimum_required(VERSION 3.16)
project(OS_lab1 C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_FLAGS -pthread)

add_executable(OS_lab1 main.c)