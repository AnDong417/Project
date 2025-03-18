cmake_minimum_required(VERSION 3.24)
project(Tetris)
set(CXX_STANDARD 20)

aux_source_directory(${CMAKE_SOURCE_DIR}/src SOURCES)
add_executable(tetris ${SOURCES})
