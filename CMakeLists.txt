cmake_minimum_required(VERSION 3.19)
project(CreateFiles C)

set(CMAKE_C_STANDARD 99)

add_executable(CreateFiles main.c Destroy/main.c)