project(test_htmlcxx2)
cmake_minimum_required(VERSION 3.0.2)

add_executable(test_htmlcxx2 test/test.cpp)
target_include_directories(test_htmlcxx2 PRIVATE 3rd .)
