project(hotel-management-app)
cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 11)

include_directories(src)

file(GLOB SOURCES
    src/*.cpp
)

add_executable(hotel-management-app ${SOURCES})