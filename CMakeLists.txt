cmake_minimum_required(VERSION 3.15)

project(seam_carving VERSION 1.0)

set(CMAKE_CXX_STANDARD 11)
set(CMALE_CXX_STANDARD_REQUIRED True)

add_execution(seam_carving seam_carving.cxx)
add_execution(unit_test unit_test.cxx)