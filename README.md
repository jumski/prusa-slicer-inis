# Prusa Slicer INIs

I use this repo to version-control PrusaSlicer profiles that I develop
during my test prints.

## Linking preset folders on Windows

Run `cmd` as administrator and then execute:

```bash
cd C:\Users\jumski\AppData\Roaming\PrusaSlicer
mklink /D print D:\Dropbox\3d-printing\prusa-slicer-inis\print
mklink /D printer D:\Dropbox\3d-printing\prusa-slicer-inis\printer
mklink /D filament D:\Dropbox\3d-printing\prusa-slicer-inis\filament
```
