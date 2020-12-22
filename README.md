# ExaGear-LibGL
 LibGL for ExaGear

Watch

https://youtu.be/OUkPmuQd5to

https://youtu.be/WF-sBShbEDM

Binary Build by GFOXSH

https://4pda.ru/forum/index.php?showtopic=992239&st=60#entry96395597

Binary Build by Andrômeda (Comment Section)

https://youtu.be/8irT01SMc2Q

## How To Compiling Mesa from Source
    #Example Mesa3D 11.2.2 Build on Ubuntu 14.04
    sudo apt-get build-dep mesa
    sudo apt-get install scons flex bison python-mako llvm
    wget https://mesa.freedesktop.org/archive/older-versions/11.x/11.2.2/mesa-11.2.2.tar.xz
    tar -xf mesa-11.2.2.tar.xz
    cd mesa-11.2.2
    scons build=release llvm=yes libgl-xlib

## How To Install LLVM 11
    wget -O - https://apt.llvm.org/llvm-snapshot.gpg.key|sudo apt-key add -
    sudo add-apt-repository 'deb http://apt.llvm.org/xenial/ llvm-toolchain-xenial-11 main'
    apt-get install llvm-11-runtime


## Credits
- [4PDA developers](https://4pda.ru/forum/index.php?showtopic=804309&st=6840#entry96039823) (GFOXSH)
- [Andrômeda](https://www.youtube.com/channel/UC_RTNrFpw0DfjKP__CAoEnw)
