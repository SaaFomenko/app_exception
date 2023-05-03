cmake_minimum_required(VERSION 3.5)

project(app_exception 
	VERSION 1.0.0
	DESCRIPTION "C++ library with functions for working with config applications"
	LANGUAGES CXX)

set(public_headers "*.h")
set(sources "*.cpp")

add_library(${PROJECT_NAME}_lib ${sources} ${public_headers})
