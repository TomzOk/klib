#------------------------------------------------------------------------------
# klib
#------------------------------------------------------------------------------
cmake_minimum_required(VERSION 3.5.1)

set (headers khash.h)

# lib
add_library(klib INTERFACE)
target_include_directories(klib INTERFACE .)
