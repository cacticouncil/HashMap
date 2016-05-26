cmake_minimum_required(VERSION 3.5)
project(HashMapTest)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_EXE_LINKER_FLAGS "-static")

set(SOURCE_FILES HashMapMain.cpp nvwa/debug_new.cpp)
add_executable(HashMapTest ${SOURCE_FILES})