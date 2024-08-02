cmake_minimum_required(VERSION 3.10)
project(refactoring)
file(GLOB SRC_FILES ${PROJECT_SOURCE_DIR}/after_ref/*.cpp 
					${PROJECT_SOURCE_DIR}/after_ref/*.h 
					${PROJECT_SOURCE_DIR}/after_ref/*.hpp)
add_executable(refactoring ${SRC_FILES})