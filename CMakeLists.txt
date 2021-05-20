cmake_minimum_required(VERSION 3.17)

project(OpenGL)
set(CMAKE_CXX_STANDARD 17)
set(EXECUTABLE_OUTPUT_PATH ./../executable)

set(SourceFiles main.cpp)
add_executable(OpenGL ${SourceFiles})