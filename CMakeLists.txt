# Minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Name of the project
project(LinkedListProject)

# C++ Standard
set(CMAKE_CXX_STANDARD 14)

# Adding the executable (test file)
add_executable(LinkedListTest main.cpp LinkedList.cpp)

# Include directories for header files
target_include_directories(LinkedListTest PUBLIC ./)
