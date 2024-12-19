cmake_minimum_required(VERSION 3.28)
project(start_game)

set(CMAKE_CXX_STANDARD 23)

add_executable(start_game main.cpp
        Unit.cpp
        Unit.h
        types.h)
