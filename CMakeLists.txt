cmake_minimum_required(VERSION 3.15)

project(GOES_Parallel)
set(CMAKE_C_STANDARD 11)

include_directories(include)
set(SOURCE
    ./src/main.c
)


add_executable(${PROJECT_NAME} ${SOURCE})