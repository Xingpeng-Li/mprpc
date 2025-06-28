cmake_minimum_required(VERSION 3.11)
project(mprpc)

set(CMAKE_BUILD_TYPE "Debug")
set(CMAKE_CXX_FLAGS -g ${CMAKE_CXX_FLAGS})
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

# 头文件
include_directories(${PROJECT_SOURCE_DIR}/src/include)

add_subdirectory(src)