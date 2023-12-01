cmake_minimum_required(VERSION 3.13)  # CMake version check
project(Demo_solution_level)

# Output all the executable to ./bin directory
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(proj_1)
add_subdirectory(proj_2)