cmake_minimum_required(VERSION 3.2 FATAL_ERROR)

project(vec C)

FILE(GLOB VEC_SRCS src/*.c)
include_directories(include)

add_library(${PROJECT_NAME} ${VEC_SRCS})
