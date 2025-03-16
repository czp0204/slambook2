cmake_minimum_required(VERSION 2.8)
project(chapter3)

# 设置 C++ 标准为 C++14
set(CMAKE_CXX_STANDARD 14)
# 要求必须使用指定的 C++ 标准
set(CMAKE_CXX_STANDARD_REQUIRED ON)
# 禁用编译器特定的 C++ 扩展
set(CMAKE_CXX_EXTENSIONS OFF)


# 加入各子工程
add_subdirectory(useEigen)
add_subdirectory(useGeometry)
add_subdirectory(visualizeGeometry)
add_subdirectory(examples)
