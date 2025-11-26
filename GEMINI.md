# GEMINI.md

## Project Overview

This is a Flutter project named `football_news`. Based on the file structure and dependencies, it appears to be a mobile application for Android and iOS, with potential support for web, Linux, macOS, and Windows.

The application uses the following key technologies:
- **Flutter:** For the cross-platform mobile application development.
- **Dart:** The programming language used for Flutter development.
- **Provider:** For state management.
- **pbp_django_auth:** For authentication with a Django backend.
- **http:** For making HTTP requests.

The application seems to follow a standard Flutter project structure, with the main application logic located in the `lib` directory. The entry point of the application is `lib/main.dart`.

The UI appears to be structured with screens in `lib/screens`, widgets in `lib/widgets`, and data models in `lib/models`.

## Building and Running

To build and run this project, you will need to have the Flutter SDK installed.

### Running the application:
1. Ensure you have a connected device or an emulator running.
2. Run the following command in the root of the project:
```bash
flutter run
```

### Building the application:
- **Android:** `flutter build apk` or `flutter build appbundle`
- **iOS:** `flutter build ios`

## Development Conventions

- The project uses `flutter_lints` for code analysis, which suggests a focus on writing clean and idiomatic Dart code.
- State management is handled using the `provider` package.
- Authentication is likely handled through a Django backend, given the `pbp_django_auth` dependency.
- The project is structured with a clear separation of concerns, with distinct folders for models, screens, and widgets.
