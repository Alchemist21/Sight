# NOTICE

Moved to [UnityAndroidCameraPlugin](UnityAndroidCameraPlugin).

This folder was not deleted in order to keep the original reference to it and, if needed, troubleshooting the .so generated by CMake.

# NativeCameraPlugin

An NDK library as the low level rendering plugin.

Update the build script for your OS to point to the location of your Android NDK folder.

Run:
```
./build.sh
```

To compile the code and copy the updated native library binary into [UnityAndroidCamera](UnityAndroidCamera).