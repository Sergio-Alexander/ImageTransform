cmake_minimum_required(VERSION 3.22)
project(ImageTransform_submission)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(uiuc)
include_directories(uiuc/catch)
include_directories(uiuc/lodepng)

add_executable(ImageTransform_submission
        tests/part1.cpp
        tests/part2.cpp
        uiuc/catch/catch.hpp
        uiuc/catch/catchmain.cpp
        uiuc/lodepng/lodepng.cpp
        uiuc/lodepng/lodepng.h
        uiuc/HSLAPixel.cpp
        uiuc/HSLAPixel.h
        uiuc/PNG.cpp
        uiuc/PNG.h
        uiuc/RGB_HSL.h
        ImageTransform.cpp
        ImageTransform.h
        main.cpp)
