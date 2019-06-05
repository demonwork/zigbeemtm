cmake_minimum_required(VERSION 3.0.2)
project(zigbeemtm C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_FLAGS "-std=c99")

#set(CMAKE_C_FLAGS "-m32")
#set(CMAKE_CXX_FLAGS "-m32")

add_library(zigbeemtm zigbeemtm.h zigbeemtm.c)

#target_link_libraries(${PROJECT_NAME} pthread)

#add_library(pt SHARED /usr/lib/x86_64-linux-gnu/libpthread.so)