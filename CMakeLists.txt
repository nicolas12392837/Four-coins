cmake_minimum_required(VERSION 3.21)

project(FourCoins)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)

set_target_properties(${PROJECT_NAME} PROPERTIES
    CXX_STANDARD 20
    CXX_STANDARD_REQUIRED YES
)
