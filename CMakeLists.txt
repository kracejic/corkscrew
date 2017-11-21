cmake_minimum_required (VERSION 3.5)

project(corkscrew C)

add_executable(corkscrew corkscrew.c)

install(TARGETS corkscrew DESTINATION bin)


