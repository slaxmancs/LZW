This file contains the C++ source code that accompanies my article LZW Revisited, found at:

http://marknelson.us/2011/11/08/lzw-revisited/

The core LZW algorithm is in the header file lzw.h.

Depending on the type of I/O you are implementing, you will need to include one of the four header files:

    lzw-a.h
    lzw-b.h
    lzw-c.h
    lzw-d.h

There are two driver programs you can use to experiment with LZW. A command line program that works under Linux or Windows is found in lzw.cpp. A Windows GUI app is descripted in LzwTest.vcproj and various additional source files.