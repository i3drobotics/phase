# Phase
C++ Library for stereo vision and 3D manipulation using I3DR's stereo camera systems.

## Latest release
Find the latest releases [here](https://github.com/i3drobotics/phase/releases/latest)

## Compatibility
### Supported platforms
 - Windows (tested on Windows 10)
 - Linux (tested on Ubuntu 20.04 & 18.04)
 - MacOS (tested on MacOS BigSur) [Coming soon]
 - Jetson (test on Jetson Nano) [Coming soon]

**NOTE: I3DR's proprietary stereo matcher I3DRSGM is not available on MacOS or Jetson platforms.**

## Install
### Linux
Download debian package from latest release.  
Install debian package using apt package manager:
```
sudo apt install -f ./phase_vx.x.x-amd64.deb
```
This should install to `/opt/i3dr/phase`
### Windows
Download Windows installer from the latest release.  
Install using the installer GUI, this should install to `C:\Program Files\i3DR\Phase`

## Documentation
For code documentation and examples on how to use Phase see [here](https://i3drobotics.github.io/phase/index.html)

## Integration
Checkout the ROS package and example cmake project for demonstration of integrating the Phase library.
- [CMake project](https://github.com/i3drobotics/phase-cmake)
- [ROS Package](https://github.com/i3drobotics/i3dr_phase-ros)

Wrappers for many common languages have been created. Checkout the repository for each project using the links below:
- [pyPhase](https://github.com/i3drobotics/pyphase)
- [Phase Sharp](https://github.com/i3drobotics/phase-sharp)
- [Phase Unity](https://github.com/i3drobotics/phase-unity)
- [PhaseJS](https://github.com/i3drobotics/phasejs)
