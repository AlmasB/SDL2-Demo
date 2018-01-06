# SDL2-Demo
A minimal example using SDL2

## Linux

Assuming developer versions of SDL2 and SDL2_image are installed:

```
cd SDL2-Demo
mkdir build
cd build
cmake ..
make
./MyGame
```

## Windows x64

Assuming Visual Studio 2015 is installed: (via MinGW64)

```
cd SDL2-Demo
mkdir build
cd build
cmake .. -G "Visual Studio 14 2015 Win64"
```

After this a ".sln" will be generated that can be opened with Visual Studio 2015.
Right click on MyGame in project explorer and select as startup project.
You can now run the demo from Visual Studio.

## Mac OS

Not tested, PRs are welcome!