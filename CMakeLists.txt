cmake_minimum_required(VERSION 3.5)

project(FilesAndStrings LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(FilesAndStrings main.cpp)

install(TARGETS FilesAndStrings
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
