# Gambian Pouched Rat(GPR)
**The Gambian Pouched Rat** can be used to detect a landmine in practice if trained.
I got naming inspiration from this thing.
The goal of project is to improve my PE file analyzing skills.
As you know, Minesweeper Doesn’t have a competitive capability inside it. (grin)

## Usage
### Version Compatibility
* Windows XP Minesweeper

### Features
* Modifying the time counting
* Look up landmines coordinates

## Build Instruction
### Prerequisites
* CMake 3.12+
* Linux - minGW 
* Windows - Visual Studio(MSVC)

#### Windows based
```bash
$ git clone https://github.com/andrewbae/gambian-pouched-rat.git
$ cd gambian-pouched-rat && mkdir build 
$ cmake . -D CMAKE_CXX_COMPILER="MSVC" -Bbuild
```
#### Linux based
```bash
$ git clone https://github.com/andrewbae/gambian-pouched-rat.git
$ cd gambian-pouched-rat && mkdir build 
$ cmake . -D CMAKE_CXX_COMPILER="x86_64-w64-mingw32-g++" -Bbuild
```

