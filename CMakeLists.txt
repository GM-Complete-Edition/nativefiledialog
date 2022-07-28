cmake_minimum_required(VERSION 3.22)

project(nativefiledialog LANGUAGES C CXX)

add_library(nativefiledialog src/nfd_common.c src/nfd_win.cpp)
target_include_directories(nativefiledialog PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/src/include")
