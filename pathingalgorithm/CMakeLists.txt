﻿# CMakeList.txt : CMake project for pathingalgorithm, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (pathingalgorithm "pathingalgorithm.cpp" "pathingalgorithm.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET pathingalgorithm PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
