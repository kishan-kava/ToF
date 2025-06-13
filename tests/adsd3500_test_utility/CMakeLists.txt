cmake_minimum_required(VERSION 2.8)
project(adsd3500_test_utility)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} PRIVATE aditof command_parser)
set_target_properties(${PROJECT_NAME} PROPERTIES CXX_STANDARD 11)
