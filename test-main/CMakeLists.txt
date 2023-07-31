cmake_minimum_required (VERSION 3.20)
project ("checkingFunctions")

add_subdirectory(../Catch2 Catch2-build)
add_executable(checkingFunctions  test-main.cpp )
target_link_libraries(checkingFunctions PRIVATE Catch2::Catch2)