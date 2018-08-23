# README for LuaJIT 2.1.0-beta3-GC64

by Andreas Zahnleiter <a.zahnleiter@gmx.de>

This version of LuaJIT is a experimental build with enabled GC64 to prevent OOM errors in Stonecraft.

See issue:
https://github.com/minetest/minetest/issues/2988#issuecomment-285090239


## Cross-compilation on Linux x64 for Windows x64

```
make XCFLAGS=-DLUAJIT_ENABLE_GC64 HOST_CC="gcc" CROSS=x86_64-w64-mingw32- TARGET_SYS=Windows
```

## Further information for cross-compiling LuaJIT

http://luajit.org/install.html

## License

LuaJIT is a Just-In-Time (JIT) compiler for the Lua programming language.

Project Homepage: http://luajit.org/

LuaJIT is Copyright (C) 2005-2017 Mike Pall.
LuaJIT is free software, released under the MIT license.
See full Copyright Notice in the COPYRIGHT file or in luajit.h.

Documentation for LuaJIT is available in HTML format.
Please point your favorite browser to:

 doc/luajit.html

