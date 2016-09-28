3dstools -- Suite of utilities including 3dsxtool, 3dsxdump, smdhtool, and cxitool.

To build:
1. `git clone https://github.com/Poryhack/3dstools.git`
2. `cd 3dstools/`
3. `./autogen.sh`
4 (if targeting Linux) `./configure`
4 (if targeting Windows 64bit) `./configure --host=x86_64-w64-mingw32`
4 (if targeting Windows 32bit) `./configure --host=i686-w64-mingw32`
5. `make`
