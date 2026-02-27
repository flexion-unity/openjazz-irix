# IRIX

Uses SDL 1.2

# Compile on IRIX

Make sure you have all required SGUG-RSE packages installed to compile with gcc on IRIX.

$ mkdir build && cd build
$ cmake .. -DCMAKE_C_COMPILER=gcc -DCMAKE_CXX_COMPILER=g++
$ make -j4

replace -j4 with your CPU count.
