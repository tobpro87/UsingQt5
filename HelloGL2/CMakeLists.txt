set(SOURCE_FILES main.cpp glwidget.cpp mainwindow.cpp window.cpp logo.cpp)

# Tell CMake to create the helloworld executable
add_executable(HelloGL2 ${SOURCE_FILES})

# Use the Widgets module from Qt 5.
qt5_use_modules(HelloGL2 Core Gui Widgets)

target_link_libraries(HelloGL2 ${QT_LIBRARIES} ${Qt5Gui_EGL_LIBRARIES})


