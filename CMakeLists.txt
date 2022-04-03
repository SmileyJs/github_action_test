cmake_minimum_required(VERSION 3.1.0)

project(github_action_test VERSION 1.0)

add_executable(github_action_test hello.cpp)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)