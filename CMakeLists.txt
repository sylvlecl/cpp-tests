cmake_minimum_required(VERSION 3.26)
project(cpp_tests)

set(CMAKE_CXX_STANDARD 17)

add_executable(hello)
target_sources(hello PRIVATE hello.cpp)

