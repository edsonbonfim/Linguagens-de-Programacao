cmake_minimum_required(VERSION 3.10)
project(LPTrabalho1 C)

set(CMAKE_C_STANDARD 99)

add_executable(LPTrabalho1 main.c)

include_directories("/home/xyz/gc/include")
target_link_libraries(LPTrabalho1 "/home/xyz/gc/lib/libgc.a")