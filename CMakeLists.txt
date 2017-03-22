cmake_minimum_required(VERSION 3.6)
project(2)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_EXE_LINKER_FLAGS -static)
set(SOURCE_FILES main.cpp)
add_executable(2 ${SOURCE_FILES})