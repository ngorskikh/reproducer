cmake_minimum_required(VERSION 3.10)

project(reproducer)

add_subdirectory(curl)

add_compile_options(-O3)

add_executable(helloworld hello.cpp)
