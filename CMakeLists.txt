cmake_minimum_required(VERSION 3.20)
project(comp_428_assignment_2 C)

set(CMAKE_C_STANDARD 11)

include_directories(/usr/local/Cellar/open-mpi/4.1.1_2/include)

add_executable(comp_428_assignment_2
        main.c)
