# social_media_app

A New Flutter Projects with CD/CI completed with Github Actions and Backend Development,
Fully Tested with Flutter Driver and Unit Test.

## Getting Started
This project is use fvm to manage flutter version, please install fvm first
```powershell
choco install fvm
flutter pub global activate fvm
```
**Note:-** Please install choco first, if you are using windows

Since this project is build by windows user so I can tell about windows only.
I will add more information linux later.
For mac user. Please donate me so I can buy a cheap macbook to test it.

### Windows:
```powershell
fvm install 3.13.0
git clone https://DeepeshKalura/social_media_app_flutter_with_backend
cd social_media_app_flutter_with_backend
fvm flutter pub get
fvm flutter run
```
**Note:-** Currently not tested I will test it later and update it any error occur please create issue.

### Vscode
Added .vscode folder for vscode user, you can use it to debug and run the project.
added application.json file for vscode user, you can use it to debug and run the project.
```json
{
  "dart.flutterSdkPath": ".fvm/flutter_sdk",
  // Remove .fvm files from search
  "search.exclude": {
    "**/.fvm": true
  },
  // Remove from file watching
  "files.watcherExclude": {
    "**/.fvm": true
  }
}
```
