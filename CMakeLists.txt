cmake_minimum_required (VERSION 2.8)
project (msgque_demo)
include_directories(./src/)
add_subdirectory(src)
add_executable(demo ./samples/quickstart/main.c)
target_link_libraries(demo msgque)
