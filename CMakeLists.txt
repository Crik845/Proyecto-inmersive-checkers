cmake_minimum_required(VERSION 3.23)
project(untitled3)

set(CMAKE_CXX_STANDARD 14)
find_package(SFML 2.5 COMPONENTS graphics audio)

add_executable(untitled3 main.cpp)
target_link_libraries(untitled3 sfml-graphics sfml-audio)