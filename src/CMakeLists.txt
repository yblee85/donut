if (WIN32)
    SET(BINARY ${CMAKE_PROJECT_NAME}.exe)
else()
    SET(BINARY ${CMAKE_PROJECT_NAME})
endif(WIN32)

file(GLOB headers "*.h")
file(GLOB sources "*.c")
set(PROJ_SRC ${headers} ${sources})

add_executable(${BINARY} ${PROJ_SRC})

#target_include_directories( ${LIB_BINARY} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

