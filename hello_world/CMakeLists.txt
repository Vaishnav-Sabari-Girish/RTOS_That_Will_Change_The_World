cmake_minimum_required(VERSION 3.10)
project(hello_world)

set(CMAKE_C_STANDARD 11)

include_directories(include)

add_executable(hello_world src/main.c)
