cmake_minimum_required(VERSION 3.6)         # CMake version check
project(huffman)                            # Create project "simple_example"
set(CMAKE_CXX_STANDARD 11)                  # Enable c++11 standard

set(SOURCE_FILES huffman.cpp)               # Add main.cpp file of project root directory as source file
add_executable(huffman ${SOURCE_FILES})     # Add executable target with source files listed in SOURCE_FILES variable