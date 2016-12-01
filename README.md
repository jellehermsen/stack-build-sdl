Stack-build-sdl
===============

This is a docker setup which I'm using with Haskell Stack to build the game I'm
making. The main docker image from the awesome folks at FP Complete doesn't
contain all the dev packages for SDL, so you can't use SDL2-Image, or
SDL2-Mixer out of the box. 

This fork basically installs the additional packages that you would like
(libsdl2-gfx-dev, libsdl2-image-dev, libsdl2-mixer-dev, libsdl2-net-dev,
libsdl2-ttf-dev) for SDL2 game development.
