cmake_minimum_required(VERSION 3.16)

project(NewWorldServer LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(NewWorldServer main.cpp)

add_subdirectory(log)

target_link_libraries(NewWorldServer PRIVATE spdlog::spdlog)