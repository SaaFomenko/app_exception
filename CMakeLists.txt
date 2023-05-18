cmake_minimum_required(VERSION 3.10)

project(app_exception
	VERSION 1.0.0
	DESCRIPTION "C++ library with functions for working with config applications"
	LANGUAGES CXX)

file(GLOB
	public_headers "*.h"
	sources "*.cpp")

add_library(${PROJECT_NAME}_lib ${sources} ${public_headers})
