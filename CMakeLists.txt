cmake_minimum_required(VERSION 3.8)
project(HeloApp )

add_executable(helloappbinary main.cpp)
target_compile_features(helloappbinary PRIVATE cxx_std_20)