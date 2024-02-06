cmake_minimum_required(VERSION 3.22)
project(world)

set(CMAKE_CXX_STANDARD 17)

include_directories("../hello")
target_link_libraries(hello)

add_executable(world main.cpp)
