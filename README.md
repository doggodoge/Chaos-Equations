> Forked from https://github.com/HackerPoet/Chaos-Equations

# Chaos-Equations
Simple mathematical art – Cross-platform port of https://github.com/HackerPoet/Chaos-Equations

**Video:** https://youtu.be/fDSIRXmnVvk

## Build Instructions

Provided is the Unix way of building the project. This hasn't been tested on macOS. Tested to work on a Raspberry Pi.

Required dependencies on debian or ubuntu:

```bash
sudo apt install build-essential cmake libsfml-dev
```

In the projects directory, do the following.

```bash
mkdir Release
cd Release/
cmake -G "Unix Makefiles" -DCMAKE_BUILD_TYPE=Release ..
make
```

The build artifact will show up in the `Release/` folder and can be executed right away.

