cmake_minimum_required(VERSION 3.16)

set(CMAKE_CXX_COMPILER g++)
set(CMAKE_C_COMPILER gcc)

project(project_name_here)

add_executable(${PROJECT_NAME}
  src/main.cpp
)