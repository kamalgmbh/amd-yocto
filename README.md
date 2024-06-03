# AMD YOCTO 


![Screenshot](https://i.imgur.com/J5RDcIz.png)

## What is this?

This is a tutorial  to make a game. This project
is for people who are just starting out yocto SDK 

The code isn't perfect. It could certainly be improved in some areas. Any kind
of feedback is welcome. Be sure to ask me questions if something is unclear.


## Installing SDL2

This uses the [SDL2 Library](https://www.libsdl.org/) for input and rendering.
CMake will find it if it's on your system. For details on how to install SDL2,
see the [installation page](https://wiki.libsdl.org/Installation).

If you're on MacOS,

```
brew install sdl2
```

If you're on a Debian based system,

```
sudo apt-get install libsdl2-dev
```

If you're on Windows,

```
vcpkg install sdl2
```

## Building

[EnTT](https://github.com/skypjack/entt) is bundled with the project to make
building this as easy as possible.

```
git clone git://github.com/kamalgmbh/amd-yocto
cd amd-yocto
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build .
./amd-yocto
```
