# ExaGear-LibGL
 LibGL for ExaGear

Binary Build by GFOXSH

https://4pda.ru/forum/index.php?showtopic=992239&st=60#entry96395597

## How To Compiling Mesa from Source
- Example Mesa3D 11.2.2 Build on Ubuntu 14.04 
    sudo apt-get build-dep mesa
    sudo apt-get install scons flex bison python-mako llvm
    wget https://mesa.freedesktop.org/archive/older-versions/11.x/11.2.2/mesa-11.2.2.tar.xz
    tar -xf mesa-11.2.2.tar.xz
    cd mesa-11.2.2
    scons build = release llvm = yes libgl-xlib

## Credits
- [4PDA developers](https://4pda.ru/forum/index.php?showtopic=804309&st=6840#entry96039823) (GFOXSH)
