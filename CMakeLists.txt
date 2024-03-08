cmake_minimum_required(VERSION 3.15)

project(CMakeTest0012)

add_executable(CMakeTest0012 main.cpp)

target_compile_definitions(CMakeTest0012 PRIVATE DEFINE_HELLO)