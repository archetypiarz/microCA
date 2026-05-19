cmake_minimum_required(VERSION 4.1)

project(
  microCA
  VERSION 0.1
  LANGUAGES CXX
)

include(CTest)
add_subdirectory(src)
add_subdirectory(test)
