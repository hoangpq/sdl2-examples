SDL2, C++20 and CMake
=====================

Requirements
------------

* CMake
* Compiler that supports C++20 (recent version of `g++` or `clang++`)
* SDL2
* ninja (or `make`, just drop the `-GNinja` flag and build with `make`)

One way of building with C++20, SDL2, CMake and ninja
-----------------------------------------------------

    mkdir -p build
    cd build
    cmake -GNinja ..
    ninja
    cd ..

Running
-------

    build/main

Cleaning up the binary file and build directory
-----------------------------------------------

    rm -rf build/
