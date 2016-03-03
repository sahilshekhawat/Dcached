cmake_minimum_required(VERSION 3.3)
project(Distributed_Cache)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES src/server.c)
add_executable(Distributed_Cache ${SOURCE_FILES})