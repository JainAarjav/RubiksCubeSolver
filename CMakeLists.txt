cmake_minimum_required(VERSION 3.24)
project(RubiksCubeSolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubiksCubeSolver main.cpp genericRubikscube.cpp genericRubikscube.h)

include_directories(/usr/local/include)