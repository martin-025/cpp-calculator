cmake_minimum_required(VERSION 3.10)
project(CppCalculator CXX)

set(CMAKE_CXX_STANDARD 17)

add_executable(cpp_calculator main.cpp calculator.cpp calculator.h)
