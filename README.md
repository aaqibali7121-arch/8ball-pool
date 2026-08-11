# 8 Ball Live Assistant — complete analysis prototype

This build adds a real, dependency-free Android image-analysis solver:
- live MediaProjection capture
- green table estimation
- six-pocket geometry
- lightweight ball candidate detection
- cue-ball heuristic
- target/pocket scoring
- ghost-ball contact calculation
- angle/power/risk estimate
- live transparent guide overlay

It does NOT control or execute the game shot.

## Build on Android Studio
Open the project, sync Gradle, then Build > Build APK(s).
APK: app/build/outputs/apk/debug/app-debug.apk

## Mobile-only limitation
This chat environment cannot compile/sign an Android APK because the Android SDK/build toolchain is not available here. The ZIP is the source project prepared for APK compilation.

## Accuracy
This is a lightweight prototype, not a production-grade 8 Ball Pool physics engine. Perspective, cloth graphics, spin, cushion effects and game-specific physics can cause errors. Use it as an aiming assistant and verify every shot manually.
