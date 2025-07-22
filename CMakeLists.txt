cmake_minimum_required(VERSION 3.31.2)

project("tiny-image")

add_library("tiny-image" "src/tinyimage.cpp")
target_include_directories("tiny-image" PUBLIC "include")