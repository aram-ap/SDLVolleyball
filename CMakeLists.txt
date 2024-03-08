cmake_minimum_required(VERSION 3.28)
project(SDLVolleyball)

set(CMAKE_CXX_STANDARD 20)

find_package(SDL2 REQUIRED COMPONENTS SDL2)

add_executable(SDLVolleyball main.cpp)
target_link_libraries(SDLVolleyball PRIVATE SDL2::SDL2)
