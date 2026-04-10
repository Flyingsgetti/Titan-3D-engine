# Titan3D

A basic 3D game engine for Android, ported from a Linux software renderer to OpenGL ES.

## Features

- 3D cube rendering with lighting
- Proper Z-culling using depth testing
- Rotating cube animation
- Sky color blending

## Building

Ensure Android SDK and NDK are installed.

Run:
```
gradle build
```

The APK will be in `app/build/outputs/apk/debug/app-debug.apk`

## Target

Specifically optimized for LG G7 ThinQ (Android API 28, Snapdragon 845).

## Notes

This is a starting point with basics. The original software renderer has been converted to GPU-accelerated OpenGL ES for better performance on Android.# Titan-3D-Engine
