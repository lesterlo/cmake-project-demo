cmake_minimum_required(VERSION 3.13)  # CMake version check
project(demo_project_1)

#Add include files
include_directories(include/)
# Add source files
# FILE(GLOB SOURCE_FILES src/*.c*) # NOT recommanded, Auto find all source files
set(SOURCE_FILES 
    src/main.cpp
)


set(EXE_NAME ${PROJECT_NAME}) # setup the executable output name
add_executable(${EXE_NAME} ${SOURCE_FILES}) # Make executable