Emergency App - Option B (Modern UI)
===================================

What's included:
- lib/main.dart
- lib/screens/*.dart (login, signup, permissions, home, call)
- lib/services/emergency_service.dart
- pubspec.yaml

How to use:
1. Install Flutter SDK and create a new flutter project:
   flutter create emergency_app
2. Replace the generated pubspec.yaml with the one in this zip (or merge dependencies).
3. Replace the lib/ folder in the generated project with the 'lib' folder from this zip.
4. Run:
   flutter pub get
   flutter run

Important Android/iOS permissions:
- Add required permissions to AndroidManifest.xml and Info.plist (location, microphone, camera).
  See comments in the README and the code.

This package is a UI scaffold and demonstrates permission flows and animated UI.
Backend (Python) and actual emergency-sending logic is not implemented here.
