# My Personal Blog — Android Project

A single-owner personal photo blog built with Kotlin and Jetpack Compose.

## Included
- Single profile with name, username, bio and profile photo
- Instagram-inspired personal feed
- Owner-only PIN-protected posting area
- Photo posts and captions
- Persistent local post storage
- Owner profile editing
- Owner post deletion
- Dark premium UI
- No accounts, followers, following, comments or public posting

## Owner PIN
The prototype PIN is `1234`. Change it in `MainActivity.kt` before distributing the app.

## Build
Open this project in a current Android Studio installation and sync Gradle. Android Studio/Gradle and the Android Gradle Plugin are the standard Android build system used to compile APKs.

## Build the APK on your phone with GitHub Actions

1. Create a GitHub repository and upload the contents of this folder.
2. Make sure the repository's default branch is `main`.
3. Open the **Actions** tab and select **Build Android APK**.
4. Tap **Run workflow** (or push to `main`).
5. When the workflow finishes, open the run and download the `MyPersonalBlog-debug-apk` artifact.
6. Extract the ZIP and install `app-debug.apk` on your Android phone.

The workflow uses GitHub's cloud runner to install Java, Android SDK 35, and Gradle, then builds the debug APK. It does not require a desktop computer.
