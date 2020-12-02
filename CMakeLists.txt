cmake_minimum_required(VERSION 3.18)
project(test)
add_executable(test test.cpp)
add_subdirectory(src/logs_lib)
target_link_libraries(test PRIVATE test_lib)

