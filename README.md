<h1>Build Instructions:</h1>

<h2>Prerequisites:</h2>

CMake (version 3.13 or higher)

Windows: MSYS2 / MinGW-w64

Linux: build-essential or gcc/g++

<h2>Windows (MinGW)</h2>

open command prompt in the project's root directory

<h3>configure:</h3>

`cmake -S . -B build -G "MinGW Makefiles" -DCMAKE_C_COMPILER="gcc" -DCMAKE_CXX_COMPILER="g++"`

<h3>Build:</h3>

`cmake --build build`


<h2>Linux</h2>

Run these commands in your Terminal:

<h3>Configure:</h3>

`cmake -S . -B build`

<h3>Build:</h3>

`cmake --build build -j $(nproc)`


<h2>Notes:</h2>
If you run into any issues when configuring, delete the build folder and start over.
