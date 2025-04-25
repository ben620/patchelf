cmake_minimum_required(VERSION 3.20.0)
project(patchelf)

file(GLOB src src/*.cc src/*.h)

add_executable(patchelf ${src})