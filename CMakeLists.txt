cmake_minimum_required(VERSION 3.23)

project(LYGFX)

include_directories(${PROJECT_SOURCE_DIR}/vendor/glfw/include)
add_executable(${PROJECT_NAME} src/main.cpp)

find_package(OpenGL REQUIRED)

message("Processing root CMakeLists")
