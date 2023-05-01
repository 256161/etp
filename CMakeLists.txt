cmake_minimum_required(VERSION 3.5)

project(gitHub_action_cmake_test LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(gitHub_action_cmake_test main.cpp)

install(TARGETS gitHub_action_cmake_test
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
