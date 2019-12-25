# Poppler static libraries for MinGW64
WARNING! WORK IN PROGRESS...
Includes a static library linked test program in windows with MinGW64 compiler. All static libraries are prebuilt and included with the executable. 

Features demonstrated:
* Open PDF
* print meta fields
* print full text
* print text list

Code is adapted from https://github.com/jeroen/popplertest

Sources:
* MSYS2 (https://msys2.duckdns.org/package/mingw-w64-x86_64-poppler?repo=mingw64)

Compiler: 
- gcc (x86_64-posix-seh-rev0, Built by MinGW-W64 project) 8.1.0

IDE: 
* Eclipse IDE for C/C++ Developers
	* Version: 2018-09 (4.9.0)
	* Build id: 20180917-1800

Library: 
* poppler 0.82.0-1

## How static library was made
NSS static library:
```shell
cd /C/mingw/nss-3.48
nss/build.sh
```

