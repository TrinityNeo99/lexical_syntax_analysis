cmake_minimum_required(VERSION 3.12)
project(lexical_syntax_analysis)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lexical_syntax_analysis
        lexical_synatax_analysis.cpp)
