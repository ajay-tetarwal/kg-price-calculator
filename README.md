# KG Price Calculator

A simple offline calculator for calculating prices based on weight and quantity.

## Features

- Calculate prices based on weight and quantity
- Light and dark theme toggle
- Bundled HTML interface
- Works offline
- No runtime third-party libraries

## Important reconstruction notice

This is a new, reconstructed source project, not the original Android Studio/Termux project. The HTML interface was recovered from `assets/index.html` in the supplied APK. The Android wrapper was recreated as a minimal Java WebView activity.

The original signing key, original source tree, exact original build settings, and complete original source history cannot be recovered from this APK.

The calculator's expression evaluator has been rewritten as a small arithmetic parser rather than using dynamic JavaScript `Function()` execution.

## Build

Requirements:

- JDK 17
- Android SDK Platform 35
- Android Gradle Plugin 8.7.3 / Gradle 8.9

Run from the project directory:

    gradle assembleDebug

The debug APK will be at:

    app/build/outputs/apk/debug/app-debug.apk

For a release build, configure signing locally. Never commit signing keys or passwords.

## Package details

- Application ID: `in.ajaytetarwal.kgpricecalculator`
- Version: `1.0` (versionCode 1)
- Minimum Android: API 23
- Target Android: API 35

These values were reconstructed/selected for this project. Confirm them before publishing.

## Privacy

The reconstructed project requests no Android permissions and does not include network access. Calculations are performed locally in the app. This statement describes this source project and should be rechecked after any future changes.

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
