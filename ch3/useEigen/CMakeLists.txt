cmake_minimum_required(VERSION 2.8)
project(useEigen)

set(CMAKE_BUILD_TYPE "debug")
set(CMAKE_CXX_FLAGS "-O0")
find_package(Eigen3 REQUIRED)

# 添加Eigen头文件
include_directories("/usr/include/eigen3")
add_executable(eigenMatrix eigenMatrix.cpp)
