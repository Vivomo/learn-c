cmake_minimum_required(VERSION 3.23)
project(learn_c C)

set(CMAKE_C_STANDARD 99)

add_executable(learn_c main.c)

add_executable(hello_world hello_world.c)
add_executable(print print.c)