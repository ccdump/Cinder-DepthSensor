# Cinder-DepthSensor

Supported sensor list:

* Kinect V1 via KinectCommonBridge (Windows 7+)
* Kinect V2 via KinectCommonBridge-V2 (Windows 8+)
* Intel RealSense sensors (R200, F200, SR300, LR200, ZR300) via librealsense SDK (Windows, macOS, Linux)
* OpenNI-compatible sensors via OpenNI2 SDK (Windows, macOS, Linux, Android)

# How to build
* Fetch submodules in 3rdparty/
* Generate project file w/ premake5
** e.g. `premake4 vs2013`
** or `premake4 xcode4`
