cmake_minimum_required(VERSION 2.8)


project(MPTRR)

set(CMAKE_CXX_FLAGS  -std=c++11)


file(GLOB_RECURSE srcfiles "${CMAKE_SOURCE_DIR}/src/*.cpp")

add_executable(main ${srcfiles})
