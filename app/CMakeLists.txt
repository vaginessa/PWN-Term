cmake_minimum_required(VERSION 3.4.1)

add_library(neoterm
             SHARED
             src/main/cpp/neoterm.cpp)

target_link_libraries(neoterm)

#add_library(nexec
#             SHARED
#             src/main/cpp/exec.c)

