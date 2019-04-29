# AndroidNotificationsBarAppStateRepro

A basic app to demonstrate that the app state changed handler does not get triggered when toggling the notifications bar on Android devices.

To reproduce, run the app on an Android device with the developer tools open and compare the logs when closing and reopening the app to the logs when toggling the notification bar. App state changed logs will appear when closing and reopening the app, but will not appear when toggling the notification bar.

## React Native Environment Info:

- System:
- OS: macOS 10.14.4
- CPU: (12) x64 Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz
- Memory: 29.16 MB / 16.00 GB
- Shell: 5.3 - /bin/zsh
- Binaries:
- Node: 8.15.1 - ~/.nvm/versions/node/v8.15.1/bin/node
- npm: 6.4.1 - ~/.nvm/versions/node/v8.15.1/bin/npm
- Watchman: 4.9.0 - /usr/local/bin/watchman
- SDKs:
- iOS SDK:
- Platforms: iOS 12.2, macOS 10.14, tvOS 12.2, watchOS 5.2
- Android SDK:
- API Levels: 26, 27, 28
- Build Tools: 28.0.2, 28.0.3
- System Images: android-28 | Intel x86 Atom_64, android-28 | Google Play Intel x86 Atom
- IDEs:
- Android Studio: 3.3 AI-182.5107.16.33.5314842
- Xcode: 10.2.1/10E1001 - /usr/bin/xcodebuild
- npmPackages:
- react: 16.8.3 => 16.8.3
- react-native: 0.59.5 => 0.59.5
- npmGlobalPackages:
- react-native-cli: 2.0.1

## Android device info:

Device name: Galaxy S5 Neo
Model number: SM-G903F
