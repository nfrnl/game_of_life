﻿cmake_minimum_required (VERSION 3.21)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

project ("game_of_life")

add_subdirectory("src")
add_subdirectory("test")
