cmake_minimum_required(VERSION 3.12)
project(tinyfiledialogs)

set(CMAKE_CXX_STANDARD 17)

add_library(tinyfiledialogs tinyfiledialogs/tinyfiledialogs.c)

target_include_directories(tinyfiledialogs PUBLIC .)