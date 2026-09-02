cmake_minimum_required(VERSION 4.1)
project(CS4400_assignment_1 C)

set(CMAKE_C_STANDARD 11)

add_executable(simulator
        simulator.c
        instruction.h)