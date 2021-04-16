cmake_minimum_required(VERSION 3.17)
project(Boroka_Parcialis)

set(CMAKE_CXX_STANDARD 14)

add_executable(Boroka_Parcialis main.cpp cmake-build-debug/stack.h cmake-build-debug/stack.c)