cmake_minimum_required(VERSION 3.27)
project(AdjMatrix)

set(CMAKE_CXX_STANDARD 23)

add_executable(AdjMatrix main.cpp
        DirectedGraph.h)
