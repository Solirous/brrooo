cmake_minimum_required(VERSION 3.25)
set(CXX_STANDARD 14)
set(CXX_STANDARD_REQUIRED true)

project(glfw)

add_executable(${PROJECT_NAME} ./src/main.cpp)
