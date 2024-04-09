# sscan
This is an S-scanner code obtained in reverse, which can be directly compiled into binary files using MSVC.

# build

```bat
lib  /DEF:msvcrt.def
cl -O2 -GS- s.c
```
