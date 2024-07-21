cmake_minimum_required(VERSION "3.19.2")

project("y-cpp-hello-world")
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
add_executable("y-cpp-hello-world" "main.cpp")

install(TARGETS y-cpp-hello-world DESTINATION bin)
