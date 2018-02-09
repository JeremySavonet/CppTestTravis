# Copyrights (c) 2018 Jeremy Savonet

cmake_minimum_required( VERSION 3.9.1 )

project ( CppTravisTest CXX )

################################################################################

set( CMAKE_INCLUDE_CURRENT_DIR ON )

set( PROJECT_NAME cpptravistest )

################################################################################

set( CMAKE_BUILD_TYPE Release )

set( SOURCES src/main.cpp )

add_executable( ${PROJECT_NAME} ${SOURCES} )
