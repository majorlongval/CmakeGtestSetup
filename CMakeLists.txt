cmake_minimum_required(VERSION 3.16)
project(ExampleProject)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

add_subdirectory(src)
add_subdirectory(tst)
add_subdirectory(lib/googletest)

# The two following line enable to see headers in QT Creator
#FILE(GLOB_RECURSE LibFiles "include/*.h")
#add_custom_target(headers SOURCES ${LibFiles})
