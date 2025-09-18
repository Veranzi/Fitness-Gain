# Flutter Starter App

This is a simple Flutter starter app scaffolded with Flutter 3.24.3. It includes:

- Material 3 theme with system light/dark support
- Counter example `HomeScreen` in `lib/main.dart`

## Prerequisites

- Flutter SDK installed and on PATH
- For Android: Android Studio + Android SDK
- For iOS: Xcode (macOS only)
- For Web: A Chromium-based browser (set `CHROME_EXECUTABLE`) or use the built-in web server via `--web-port` and headless run

## Get started

```bash
flutter --version
flutter pub get
```

## Run on web

```bash
flutter run -d web-server --web-port 8080
```

Then open `http://localhost:8080` in your browser.

If you have Chrome installed, you can run:

```bash
CHROME_EXECUTABLE=/path/to/chrome flutter run -d chrome
```

## Run on Android

1. Start an emulator or connect a device.
2. Run:

```bash
flutter devices
flutter run -d <device-id>
```

If you see Gradle/Java version warnings, use Java 17 or set a compatible JDK via:

```bash
flutter config --jdk-dir=<JDK_DIRECTORY>
```

## Build for web

```bash
flutter build web --release
```

Artifacts will be in `build/web/`.

## Notes

Run a health check:

```bash
flutter doctor -v
```

Address any missing dependencies for your target platforms.
