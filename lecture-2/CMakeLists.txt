cmake_minimum_required(VERSION 3.20)
project(hi)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_BUILD_TYPE Debug)

add_executable(hi hi.cxx)