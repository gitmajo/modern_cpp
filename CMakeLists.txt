set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(modern_cpp)
cmake_minimum_required(VERSION 2.8)
aux_source_directory(. SRC_LIST)
include_directories(inc)
add_definitions(-Wall -Wextra -Werror)
add_executable(${PROJECT_NAME} ${SRC_LIST})
