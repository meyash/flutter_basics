# Flutter Commands

## Docs

[DOCS](https://flutter.dev/docs)
[PUB.DEV](https://pub.dev)

### Install

* Flutter
* Android Studio
* Android Studio Dart & Flutter Plugin
* VsCode Dart & Flutter Extension
* Java for Gradle

### Init

* which flutter
* flutter doctor
* flutter devices

### New Project

* flutter create app_name
* if packages not installed | flutter pub get
* cd app_name
* flutter run | Run w/o showing any info
* flutter run -v | For seeing background tasks

### VS_Code

* ctrl+F5 | To run in VSCode
* ctrl+shift+r | To refactor code
* st | creates stateful and stateless widegets
* ctrl+click on tag | Takes us to source of that tag

### Gradle Commands

* ./gradlew --stop | To stop all processes
* ./gradlew --status | To view running

### External packages

* Put all packages in pubspec.yaml
1.Date package for formatting Dates:
* intl: ^0.15.8

### Android vs IOS

* MaterialApp | CupertinoApp
* Scaffold | CupertinoPageScaffold

### Some fixes

* waiting to break flutter lock | killall -9 dart
* inside project | flutter clean
* Gradle errors : ?
    *a. delete all contents under /home/nima/.gradle
    *b. cd to the android folder for your flutter project and run ./gradlew sync command, it will download the gradle-xxx.zip automatically. It this gradle process succeeds, re-run the flutter run command.
