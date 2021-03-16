cmake_minimum_required(VERSION 3.17)
project(pytorch_qulacs)

set(CMAKE_CXX_STANDARD 17)

add_library(pytorch_qulacs library.cpp library.h)
