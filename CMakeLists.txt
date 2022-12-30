project(opengl LANGUAGES CXX)
cmake_minimum_required(VERSION 3.24)

find_package(OpenGL)

add_executable(opengl WIN32  Main.cpp)
target_link_libraries(opengl OpenGL32)