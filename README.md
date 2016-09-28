3dstools -- Suite of utilities including 3dsxtool, 3dsxdump, smdhtool, and cxitool.

To cross-compile for Windows on Ubuntu:
```
git clone https://github.com/Poryhack/3dstools.git
cd 3dstools/
./autogen.sh
./configure --host=x86_64-w64-mingw32
make
```

Replace `--host=x86_64-w64-mingw32` with `--host=i686-w64-mingw32` for 32-bit builds.
