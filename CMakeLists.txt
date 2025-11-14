cmake_minimum_required(VERSION 3.10)
project(BabyPy)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add include directory
include_directories(include)

# Build the executable
add_executable(BabyPy
    src/main.cpp
)