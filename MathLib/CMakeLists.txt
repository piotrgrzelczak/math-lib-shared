add_library(MathLib SHARED)

include(sources.cmake)

target_include_directories(MathLib
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}/Sources
)
