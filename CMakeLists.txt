cmake_minimum_required(VERSION 3.17)
project(flighters_ecs C)

find_package(raylib 2.5.0 REQUIRED) # Requires at least version 2.5.0

set(CMAKE_C_STANDARD 99)

add_executable(flighters_ecs main.c)

target_link_libraries(flighters_ecs raylib)