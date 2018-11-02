# SDLAndroidVS
Visual Studio 2017 projects for building SDL2 for Android

## Prerequisites
* Visual Studio 2017
* Mobile Development with C++ (via Visual Studio Installer)

SDL2 (the 2.0.9 release) is added as a submodule. Make sure you recurse submodules when you clone the repo. 

I followed the [guide here](https://trederia.blogspot.com/2017/03/building-sdl2-for-android-with-visual.html) to set this up, though I had to create an additional shared library project for hidapi that was referenced in the Android makefile.
