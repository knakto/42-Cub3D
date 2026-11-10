# cube3D

## Demo

<video src="./assets/recording.mp4" controls width="100%"></video>
what I want to show (my extra feature):
 - can move with `w/a/s/d` for mandatory require
 - have portal can taleport
 - can sprint when press `shift`
 - can move mouse on y axis
 - can jump!!

### structure file
```
-include/
|----cube.h
|----module.h
-lib/
-srcs/
|----main/
|   |----cube.c
|----module/
    |----module_internal.h
    |----module.c
    |----sub_module/
        |----submodule_internal.h
        |----file.c
Makefile
flake.nix
flake.lock
```
