# D2DF-SDL
[Doom 2D Forever](https://github.com/pss88/DF) adapted for use with the FreePascal Compiler and ported to SDL 1.2.

# Building

## Requirements
* FPC >= 3.0.0 (with the "sdl" package installed);
* FMODEx >= 4.26.xx;
* libenet >= 1.3.13;
* SDL >= 1.2.15.

## Instructions
### Windows
Run build.bat.
If it builds fine, the executable will be output to "./Bin/Doom2DF.exe".
Don't forget that it will require SDL.dll, FMODEx.dll and ENet.dll to run.
### Linux
Run
```
fpc -MDELPHI -O2 -FE../Bin -FU../Temp Doom2DF.dpr
```
in the "Game Source" directory.