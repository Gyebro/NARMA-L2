cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

add_executable(narma-l2-core
	activation.cpp
	NARMAL2Network.cpp
	main.cpp
)