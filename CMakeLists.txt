cmake_minimum_required(VERSION 3.12)
project(clibjson)

set(CMAKE_CXX_STANDARD 14)

add_executable(clibjson
        main.cpp
        memory.h
        types.h
        types.cpp
        clexer.h
        clexer.cpp
        cparser.h
        cparser.cpp
        cast.h
        cast.cpp)