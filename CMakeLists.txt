cmake_minimum_required(VERSION 3.10)
project(BabyPy)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add include directory
include_directories(include)

# Build the executable
add_executable(BabyPy
    src/main.cpp
    include/common.h
    src/bytecode/chunk.cpp
    include/chunk.h
    src/tools/memory.cpp
    include/memory.h
    include/debug.h
    src/tools/debug.cpp
    include/value.h
    src/bytecode/value.cpp
    include/vm.h
    src/tools/vm.cpp
    include/compiler.h
    src/tools/compiler.cpp
    include/scanner.h
    src/tools/scanner.cpp
    include/object.h
    src/bytecode/object.cpp
    include/table.h
    src/containers/table.c
)
