cmake_minimum_required(VERSION 3.16)

project(2hol LANGUAGES CXX)

add_subdirectory("${CMAKE_SOURCE_DIR}/../minorGems" "${CMAKE_CURRENT_BINARY_DIR}/minorGems")
add_subdirectory("${CMAKE_SOURCE_DIR}/gameSource")
add_subdirectory("${CMAKE_SOURCE_DIR}/server")
