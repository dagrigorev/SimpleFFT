cmake_minimum_required(VERSION 3.13)
project(C C)

set(CMAKE_C_STANDARD 99)

add_executable(C main.c signal.h signal.c FFT/DFT.h  FFT/DFT.c)