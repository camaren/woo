cmake_minimum_required(VERSION 3.7)
project(woo)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES GenericInequalities.hpp GenericInequalities.cpp TestGenericInequalities.cpp)
add_executable(woo ${SOURCE_FILES})