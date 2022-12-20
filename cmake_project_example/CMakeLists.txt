# cmake 3.14 버전 이상
cmake_minimum_required(VERSION 3.13)

set(PROJECT_NAME cmake_project_example)
# CXX === C++ 이란 같은 말
# C++ 17버전 사용
set(CMAKE_CXX_STANDARD 17)

project(${PROJECT_NAME})
# src/main.cpp을 컴파일해 실행파일을 만듦
add_executable(${PROJECT_NAME} src/main.cpp)