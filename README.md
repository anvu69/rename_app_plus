# Rename App
## THIS IS FORK REPO FOR ONLY RESOLVE CONFLICT DEPENDENCIES!!! ⚠️⚠️⚠️
### The only flutter package which changes app name for all platforms with sound null safety!


```If you want to autmatically change your flutter app name with a single command then you are at the right pacakge. This package gives you too many flexibilities through too many variants of its commands. Read the details below to know in more details```
- ✊  Dont forget to star the github repo if you found this package useful 😇

Main Developer : [Syed Waleed Shah](https://github.com/Syed-Waleed-Shah)
Fork/Maintainer: [anvu69](https://github.com/anvu6)

## Features 🔥
✅  Rename Android Project
✅  Rename IOS Project
✅  Rename WEB Project
✅  Rename Windows Project

## How To Rename ? 🛠
##### 1) ADD THE PACKAGE TO DEPENDENCIES IN pubspec.yaml
```sh
flutter pub add rename_app_plus
```
OR
```sh
dependencies:
  rename_app_plus: ^latest_version
```
##### 2) PROVIDE THE APP NAME
You can provide app name in the following ways
##### Same name for all apps
```sh
flutter pub run rename_app_plus:main all="My App Name"
```
#####  Seperate name for specified platform(s) and same for all others
```sh
flutter pub run rename_app_plus:main android="Anroid Name" ios="IOS Name" others="Others Name"
```
#####  Seperate name for each platform
```sh
flutter pub run rename_app_plus:main android="Android Name" ios="IOS Name" web="Web Name" mac="Mac Name" windows="Windows Name" 
```

## More Flexibilities 😎
| REQUIREMENT | COMMAND |
| ------ | ------ |
| All Same| ```flutter pub run rename_app_plus:main all="App Name"``` |
| Only Android | ```flutter pub run rename_app_plus:main android="Android App"``` |
| Only IOS | ```flutter pub run rename_app_plus:main ios="IOS App"``` |
| Only WEB | ```flutter pub run rename_app_plus:main web="Web App"``` |
| ONLY Windows | ```flutter pub run rename_app_plus:main windows="Windows App"``` |
| With Others |```flutter pub run rename_app_plus:main android="Android App" ios="IOS App" others="Others App Name"``` |


