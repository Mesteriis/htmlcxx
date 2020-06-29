enable_testing()
include_directories(../3rd)
add_executable(htmlcxx2_tests test_htmlcxx2.cpp)
add_test(htmlcxx2_tests htmlcxx2_tests)
