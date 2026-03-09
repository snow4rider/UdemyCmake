# 0.) Create Source and CMakeFiles.txt
# 1.) mkdir build
# 2.) cd build
# 3.) cmake .. - Generating the build files / configure the project
# 4.) cmake --build .
# 5.) ./Executeable


cmake_minimum_required(VERSION 3.22)

project(CppProjectTemplate VERSION 1.0.0 LANGUAGES C CXX)

add_executable(Executable main.cpp)
