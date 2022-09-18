cmake_minimum_required(VERSION 3.0.0)
SET(prj_name "donut")
project(${prj_name} VERSION 0.1.0)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR})
include_directories(./include)


add_subdirectory(src)
set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
