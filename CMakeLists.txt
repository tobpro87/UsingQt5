cmake_minimum_required(VERSION 3.5.1)

######## Project settings ########
project(UsingQt5 CXX)

# SET(OE_QMAKE_PATH_EXTERNAL_HOST_BINS "/usr/bin/")

# Instruct CMake to run moc automatically when needed.
set(CMAKE_AUTOMOC ON)
set(CMAKE_INCLUDE_CURRENT_DIR ON)

# Qt library
find_package(Qt5Core)
find_package(Qt5Gui)
find_package(Qt5Widgets)
find_package(Qt5OpenGL)

add_subdirectory(./HelloGL2)





