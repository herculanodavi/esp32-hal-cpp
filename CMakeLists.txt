cmake_minimum_required(VERSION 3.16)

set(COMPONENTS "main")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
add_compile_options(-fdiagnostics-color=always)
project(template)
