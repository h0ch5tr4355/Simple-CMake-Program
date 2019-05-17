# My very basic CMakeLists.txt

cmake_minimum_required(VERSION 3.10.2)
project(app_project)
add_executable(myapp main.cpp)
install(TARGETS myapp DESTINATION bin)
