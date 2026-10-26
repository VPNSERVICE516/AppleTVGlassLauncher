# Apple TV Glass — Android TV launcher scaffold

This is a **source-code starter project**, not a compiled or device-tested APK.

## What's included
- Android native Activity that declares HOME and LEANBACK_LAUNCHER.
- TV app visibility query for Android 11+.
- Simple remote-focusable tile layout with a dark glass-inspired style.
- A list of installed Leanback apps in a basic dialog.

## Important limitations
- The project has not been built or tested against your TV.
- Tile icons and launch mapping are placeholders; labels like YouTube/Kino/Music are not guaranteed to map to installed apps.
- No debloating, package disabling, ADB, network access, or system-setting changes are performed.
- `minSdk 26` is a provisional baseline; confirm the TV's Android API level before building.
- To build an APK, use Android Studio on a computer or a compatible Android build environment. A phone alone may be awkward for Gradle/SDK builds.
- Install and test the APK while keeping the stock launcher enabled. Do not disable the stock launcher until Home key, reboot, app launching, and recovery have all been verified.
- The target SDK and theme may need adjustment for the specific TV firmware.

## Next steps
1. Find the TV model in Settings → Device Preferences/System → About.
2. Note Android TV/Google TV version and build number.
3. If installing via phone, use a trusted local file transfer method and the TV's supported package installer; do not enable network ADB unless necessary.
4. Build and install as a secondary app first, then verify remote navigation.
