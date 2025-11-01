UltraCam - Ready-to-import Android Studio project
Target: Android 13+ (API 33)
Language: Kotlin, Jetpack Compose, CameraX

How to open:
1. Download and unzip the project.
2. Open Android Studio (Electric Eel or newer recommended).
3. Choose 'Open' and select the project's root folder (UltraCam).
4. Let Android Studio sync Gradle; you may be prompted to update Gradle or the Android Gradle Plugin.
5. Run on a device that supports 4K/UHD CameraX recording (flagship phones).

Notes:
- This project uses CameraX video APIs with UHD quality selected. On some devices, UHD/60fps may not be available.
- WRITE_EXTERNAL_STORAGE permission is included for broad compatibility; for Android 13+ prefer scoped storage approaches for production.
- To enable ProRes or low-level bitrate control, replace CameraX recorder usage with a Camera2 + MediaCodec or use CameraX experimental APIs.
