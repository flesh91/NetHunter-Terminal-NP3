cmake_minimum_required(VERSION 3.10)

add_library(neoterm
             SHARED
             src/main/cpp/neoterm.cpp)

target_link_libraries(neoterm)

#add_library(nexec
#             SHARED
#             src/main/cpp/exec.c)

