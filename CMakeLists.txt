cmake_minimum_required(VERSION 3.28)
project(untitled7 C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled7 main.c
        libs/data_structures/matrix/matrix.c
        libs/data_structures/matrix/matrix.h
        libs/until/until.c
        libs/until/until.h)
