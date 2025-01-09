cmake_minimum_required(VERSION 3.10)
project(scheduler)

set(CMAKE_C_STANDARD 11)

include_directories(include)

add_executable(scheduler src/main.c)
