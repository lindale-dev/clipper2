project(clipper2)

set(SOURCES
  clipper.h
  clipper.cpp
  clipper_core.hpp
  clipper_offset.h
  clipper_offset.cpp
)

add_library(${PROJECT_NAME} STATIC ${SOURCES})

target_compile_features(${PROJECT_NAME} PRIVATE cxx_std_17)
