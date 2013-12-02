cmake_minimum_required(VERSION 2.6)

project(ProjectC C)

add_executable(ExeC exec.c)

install(TARGETS ExeC RUNTIME DESTINATION bin)
