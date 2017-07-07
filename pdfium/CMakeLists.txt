# For more information about using CMake with Android Studio, read the
# documentation: https://d.android.com/studio/projects/add-native-code.html

CMAKE_MINIMUM_REQUIRED(VERSION 3.4.1)

SET(CMAKE_VERBOSE_MAKEFILE on)

ADD_SUBDIRECTORY(${PROJECT_SOURCE_DIR}/src/main/cpp)

MESSAGE(STATUS "This is SOURCE dir " ${PROJECT_SOURCE_DIR})
MESSAGE(STATUS "This is BINARY dir " ${PROJECT_BINARY_DIR})