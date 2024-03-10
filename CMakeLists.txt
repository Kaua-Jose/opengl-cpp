cmake_minimum_required(VERSION 3.0.0)
project(opengl-cpp VERSION 0.1.0)

add_executable(opengl-cpp src/main.cpp)

target_link_libraries(opengl-cpp 
    glfw
    GLEW
    GL
)

