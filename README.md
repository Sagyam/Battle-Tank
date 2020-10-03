# Battle-Tank

![Screenshot of the game](https://raw.githubusercontent.com/Sagyam/Battle-Tank/main/sample.jpeg)

## About
This repository contains my LITE-2019 winning game Battle Tank. It was made with Unreal Engine using blueprint and C++. 

## Requirements:
Software
1. Engine: [Unreal Engine 4.24.3](https://www.unrealengine.com/en-US/eulacheck?state=https%3A%2F%2Fwww.unrealengine.com%2Fen-US%2Ffeed&studio=false) or newer
2. IDE: [Microsoft Visual Studio Community 2017](https://visualstudio.microsoft.com/) or [Xcode](https://developer.apple.com/xcode/) 
   - The editor works on Linux, but Linux users must configure their environment to their specific system.

Hardware
1. A system that meets the [Unreal Editor requirements](https://docs.unrealengine.com/en-US/GettingStarted/RecommendedSpecifications/index.html)
2. For Raytracing, a GPU that supports DirectX Ray Tracing.

## Compiling it yourself
1. Ensure you have the software listed above installed on your computer.
2. Download this repository as a zip or clone with --depth=1
### Editor only
4. Open the `.uproject` and compile now if it asks
5. Play! 
### From IDE
4. Right-click the `.uproject` file in the Finder/File Explorer and press `Generate Xcode/Visual Studio Project`
   - If this option is not visible, open the `.uproject` and go to `File->Generate Xcode/Visual Studio Project`
5. Press the Compile and Run button in your IDE (CMD+R in Xcode, green Run button in VS)
6. Play!

## Issues
If you find an issue, use the [Issues](https://github.com/Ravbug/TanksUE4/issues) section of this repository to report it. Be sure to include specifically what the issue is, as well as what you've done to try to fix it. The more information you include, the better. However, I may not be able to fix it quickly.


## Tasks
- [x] Correct shared camera 
- [x] Input using player controllers
- [x] Title screen
- [x] Tank Physics
- [x] Build level
- [x] Set up lightmass and scene lighting
- [x] Implement Barebones AI
- [x] Add 3D surround Sound
- [x] Tank Colors
- [x] Graphics Settings
