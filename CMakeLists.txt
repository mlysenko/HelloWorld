cmake_minimum_required(VERSION 3.1)

project(main)

add_executable(main main.cpp)

install(TARGETS main DESTINATION bin)

enable_testing()
add_test(NAME main COMMAND main)
