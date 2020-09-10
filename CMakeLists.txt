cmake_minimum_required(VERSION 3.14)

if(WIN32)
	add_compile_options("/std:c++latest")
endif(WIN32)

set(CMAKE_CXX_STANDARD 17)

project(BasicTerminal)

add_executable(BasicTerminal
	${PROJECT_SOURCE_DIR}/main.cpp
)
