Using Qt5
=============================

Using Qt5 as a Library - Examples based on Qt documentation

## Preface
Please look at the [Qt5 documentation](http://doc.qt.io/) as a reference.

## Building


### Build

*Create a build directory.*

    mkdir build && cd build
  
*Generate a build system using any [desired generator](https://cmake.org/cmake/help/v3.0/manual/cmake-generators.7.html) in CMake. e.g "Unix Makefiles"*

    cmake -G "Unix Makefiles" ../
    
*Build - you can use any IDE if applicable to the generator, but you can also just build straight from CMake.*

    cmake --build .

## Provided Examples

[HelloGL2](./HelloGL2)


