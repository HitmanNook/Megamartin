cmake_minimum_required(VERSION 3.28)
project(martin)

set(CMAKE_CXX_STANDARD 17)

add_executable(martin Pet_Store.cpp
        Pet_Store.h
        Pet.cpp
    Pet.h)
