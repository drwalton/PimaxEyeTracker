# PimaxEyeTracker
A utility library with language bindings for aSeeVR UserSDK, to use with the 7invensun Droolon Pi1 eye tracker designed for Pimax headsets.

# Features
- C++ library
  - Manages connection and eye tracking state with aSeeVR Runtime.
  - Provides both raw eye tracking state data and sanitized expression data better suited for VR applications with simple use cases (e.g. avatar eye tracking in social VR applications).
- C# & Unity bindings
  - Enables the C++ library to be used in C# or Unity applications.
  - A Unity component to control the eye tracker and view eye tracking state.

# Related Projects
[VRCPimaxEyeTracker](https://github.com/NGenesis/VRCPimaxEyeTracker)

# Building
Build by opening the project in Visual Studio, and running "Build All" in Release mode.

I have only tested this in Visual Studio Community 2022.

## Directories
During the build it will attempt to move the built libraries to a couple of directories outside this repo which you may need to create to avoid errors.

These are: 

`\PimaxEyeTracker\..\PimaxEyeTrackerUnity\Assets\PimaxEyeTracker\Plugins`
`\PimaxEyeTracker\..\VRCPimaxEyeTracker\PimaxEyeTracker`

Just to be clear you should create directories `\PimaxEyeTrackerUnity\Assets\PimaxEyeTracker\Plugins` and `\VRCPimaxEyeTracker\PimaxEyeTracker` in the same directory you've cloned this repository to.