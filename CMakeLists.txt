cmake_minimum_required (VERSION 3.5)
project(LazyReef)

set(LAZY_REEF_VERSION_MAJOR 1)
set(LAZY_REEF_VERSION_MINOR 0)
set(SOURCES ${PROJECT_SOURCE_DIR}/src/Main.cpp)

include_directories("${PROJECT_SOURCE_DIR}/include")
add_executable(LazyReef ${SOURCES})
#enable_testing()

#add_subdirectory(test)