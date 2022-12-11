cmake_minimum_required(VERSION 3.0.0)
project(Sasso_C_CppGenNetLib VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(Sasso_C_CppGenNetLib src/Sasso_C_CppGenNetLib.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
set(CMAKE_C_STANDARD 17)
set(CMAKE_CXX_STANDARD 20)
include(CPack)
