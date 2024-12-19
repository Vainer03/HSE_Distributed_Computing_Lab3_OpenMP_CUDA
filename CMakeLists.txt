cmake_minimum_required(VERSION 3.16)
project(HSE_DC_Lab3_CLion CUDA)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CUDA_STANDARD 20)

add_executable(HSE_DC_Lab3_CLion main.cu)

set_target_properties(HSE_DC_Lab3_CLion PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
