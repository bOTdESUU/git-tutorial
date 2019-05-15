project(git_tutorial)
cmake_minimum_required(VERSION 3.4 FATAL_ERROR)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/../bin)

include_directories(include)

file(GLOB SOURCES "src/*.c")

add_executable(foo /DIST/home/lab_espl_stud19/ESPL_code/build/CMakeFiles/3.7.2/CompilerIdC/CMakeCCompilerId.c)

